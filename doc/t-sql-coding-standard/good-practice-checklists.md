# Good practice checklists

Use this checklist to demonstrate you follow our coding standards.

We cross-reference each checklist item to a relevant section in our
standards and guides; Exceptions are noted where they may apply.

## 9.1 general good practice

| **Item** |  |  | **Guide or standard** | **Exceptions** |
| --- | --- | --- | --- | --- |
| 1 | You avoid placing business logic in the database | ☐ | *T-SQL coding standard, [7.1](avoid-using-t-sql-to-execute-business-logic.md)* | This is a general rule. But there may be times when there are good reasons not to follow it. |
| 2 | You follow the coding conventions described in this standard | ☐ | *T-SQL coding standard, All* |  |
| 3 | You keep T-SQL scripts and database code in source control | ☐ | *T-SQL coding standard, [7.3](general-good-practice.md)* |  |
| 5 | You analyse T-SQL against Redgate code analysis rules | ☐ | *T-SQL coding standard, [7.6](apply-code-analysis-rules.md)* |  |
| 6 | You format T-SQL using our common configuration settings | ☐ | *T-SQL coding standard, [7.20](follow-our-code-layout-rules.md)* |  |


    Index](https://www.brentozar.com/blitzindex/) makes use of SQL
    Server's Missing Index Dynamic Management Views (DMVs)

    CROSS APPLY -- most likely when shredding XML/JSON data.




    metadata but doesn\'t update the cache when underlying objects
    change.

    Redgate discourages interweaving Data Definition Language (e.g.
    CREATE TABLE) and Data Manipulation Language statements (e.g.
    SELECT).

    example, having many procedures prefixed with 'Get' makes any
    specific stored procedure difficult to spot. See the section
    '[Exceptions prove the rule'](exceptions-prove-the-rule.md).

    coding standards based on language and technology and we will.
    However, SQL is a set-based language -- it's acceptable that
    different rules apply.

    based on the leading letters in a camel case table name.

    meaning.

    aid performance.



    Prompt 9\\StylesV2*

 Group Assignment IV: Advanced Oracle PL/SQL Programming

Group Members
- Assouman SIBOMANA Student ID: 27191

Application Description
This project demonstrates advanced Oracle PL/SQL programming concepts, including:
- Records (user-defined and %ROWTYPE)
- Collections (associative arrays, nested tables, VARRAYs)
- Implicit and explicit cursors
- Bulk processing with BULK COLLECT and FORALL
- Stored procedures and functions
- Exception handling (predefined, user-defined, and RAISE_APPLICATION_ERROR)

The chosen application scenario is Student Course Management, which manages:
- Student registration and details
- Course information
- Enrollments linking students to courses

The implementation shows how PL/SQL features can solve practical problems in database applications, with emphasis on performance and error handling.

How to Run
1. Create Schema
   - Run `00_schema/01_create_tables.sql` to create tables, relationships, and constraints.
   - Run `00_schema/02_insert_sample_data.sql` to insert sample records.

2. Compile PL/SQL Code
   - Compile stored procedures in `01_procedures/`.
   - Compile stored functions in `02_functions/`.

3. Test Application
   - Run test cases in `03_tests/test_success_cases.sql` for successful operations.
   - Run `03_tests/test_error_cases.sql` to verify exception handling.
   - Check screenshots in `screenshots/` for execution outputs.

4. Documentation
   - Review `docs/IMPLEMENTATION_NOTES.md` for implementation details and performance considerations.

5. Execution Environment
   - Use Oracle Database Free (23c/26ai) with SQL Developer.

6. Verification
   - Ensure all scripts run without errors.
   - Confirm records, collections, cursors, and bulk operations are demonstrated.
   - Validate exception handling with screenshots.



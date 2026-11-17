-- =====================================================
-- Question 1: Back up a single database
-- =====================================================
-- Command (run in the terminal, not inside MySQL):
-- mysqldump -u root -p database_name > database_name_backup.sql

-- Explanation:
-- This command uses mysqldump to export one database. The -u root
-- option logs in as the root user, and -p makes MySQL prompt for the
-- password so it is not typed in plain text. The > symbol saves the
-- output into database_name_backup.sql, which contains all the SQL
-- needed to recreate the tables and data. Regular backups matter
-- because they protect against data loss from hardware failure,
-- human error, or corruption, and they let you recover quickly
-- after a disaster.


-- =====================================================
-- Question 2: Back up all databases
-- =====================================================
-- Command (run in the terminal, not inside MySQL):
-- mysqldump -u root -p --all-databases > all_databases_backup.sql

-- Explanation:
-- The --all-databases option exports every database on the server
-- into a single file, all_databases_backup.sql. A full server backup
-- should be taken before a migration because migrations can go wrong,
-- and having a complete copy of everything lets you roll back to the
-- original state without losing any data. Regular full backups also
-- ensure data integrity and make disaster recovery possible.

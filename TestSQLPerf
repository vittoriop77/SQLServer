-- Create a sample Database
CREATE DATABASE TestDB;
GO

USE TestDB;
GO

-- Create a sample Table
CREATE TABLE Persons (
    PersonID int,
    LastName varchar(255),
    FirstName varchar(255),
    Address varchar(255),
    City varchar(255)
); 
GO

-- Insert data (in my test I did it 40000 times with SQLQueryStress https://github.com/ErikEJ/SqlQueryStress and takes about 5 minutes)
INSERT INTO Persons VALUES (1, 'Pavesi','Vittorio', 'Via le dita dal naso', 'Milan');
GO

-- Read data (in my test I did it 200 times with SQLQueryStress https://github.com/ErikEJ/SqlQueryStress and takes about 1 minute)
SELECT * FROM Persons;
GO


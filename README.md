# .Net-Core-Web-API





SCRIPT to create a table in database
CREATE TABLE [dbo].[tblEmployee] (
    [Id]        INT            IDENTITY (1, 1) NOT NULL,
    [FirstName] NVARCHAR (MAX) NULL,
    [LastName]  NVARCHAR (MAX) NULL,
    [Tel]       NVARCHAR (MAX) NULL,
    [Email]     NVARCHAR (MAX) NULL,
    PRIMARY KEY CLUSTERED ([Id] ASC)
);

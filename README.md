This automation retrieves unanswered emails from the past 30 days from a Gmail account. Next, it creates a data table and  saves the attachments from emails containing the keyword "invoice" in the subject line. Afterwards, it adds the sender's address, email subject, and email date to the created data table for all retrieved and unanswered emails

It then writes the data from the data table into an Excel sheet. Finally, it sends the Excel file along with saved attachments using SMTP and Gmail

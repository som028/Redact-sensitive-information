# Redact-sensitive-information
I this project goal is to create a Redactor and Unredactor. The goal is to take text files, and remove "sensitive" information and then take text files and develop and algorithm to unredact redaacted documents.

In this project, I created a medium sized python project to use text processing algorithms, created a type of
classifier, and created test cases. 

This project, is divided into two phases.

## Phase One: Regex, Named Entity Recognition Testing

Whenever sensitive information is shared with the public, the data must go through a redaction process. That
is, all sensitive names, places, and other sensitive information must be hidden. Documents such as police
reports, court transcripts, and hospital records all containing sensitive information. Redacting this information is
often expensive and time consuming.

## Phase Two: Classification

The unredactor will take a redacted document and the redaction flag as input, in return it will give the most
likely candidates to fill in the redacted location.

The unredactor only needs to unredact names.

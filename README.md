# Kata16 Szmorad Gergely

## Order handleing system development

### The Task
In our company the organisation of the orders was very caotic in the past. I got the task to make an application for our ordering system. I don't have all the nessesary rules. So I start developing the program and leave notifications in the commit section from the progress.

### The Versions
  1. Version 1.0
      -Contain basics options for ordering:
        - If the payment is for a physical product, generate a packing slip for shipping.
        - If the payment is for a book, create a duplicate packing slip for the royalty department.
        - If the payment is for a physical product or a book, generate a commission payment to the agent.
  2. Version 1.1
        - If the payment is for a membership, activate that membership.
        - If the payment is an upgrade to a membership, apply the upgrade.
        - If the payment is for a membership or upgrade, e-mail the owner and inform them of the activation/upgrade.
  3. Version 1.2
        - If the packing was succesful, send an email for the client.
        - If the payment was sucessful, but we dont have the specific item in the storage, send an email to the client.
        - Send emails for our members about our new goods.

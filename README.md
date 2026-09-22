პროექტის აღწერა:
პროექტში ვიყენებთ მონაცემთა ბაზას - best_selling_phones.db, რომელიც შეიცავს ბაზარზე ყველაზე გაყიდვადი მობილური ტელეფონების მონაცემებს. მომხმარებელს შეუძლია მონაცემთა წაკითხვა, დამატება, განახლება და წაშლა.  ვმუშაობთ SQLite მონაცემთა ბაზებთან Python-ით და ვიზუალიზაციას ვუკეთებთ ინფორმაციას matplotlib ბიბლიოთეკით.

როგორ მუშაობს პროგრამა:
პროგრამის დასაწყისში ხდება ყველა იმ ტელეფონის წაკითხვა და გამოტანა, რომლის მწარმოებელიც არის "Nokia". შემდეგ მომხმარებელს შეუძლია ახალი ტელეფონის მონაცემის შეყვანა და ბაზაში დამატება. პროგრამა ასევე ითხოვს კონკრეტული მოდელის ფორმის (form factor) განახლებას და სხვა მოდელის წაშლას. ყოველი მოქმედება ინახება ბაზაში.

მონაცემების ვიზუალიზაცია:
პროგრამა ასახავს გრაფიკულ დიაგრამებს იმის საჩვენებლად, თუ რამდენი ტელეფონია ბაზაში თითოეული მწარმოებლის მიხედვით. გამოიყენება bar chart, pie chart და scatter plot.


**Project Description:**
In this project, we use a database called `best_selling_phones.db`, which contains data on the best-selling mobile phones on the market. The user can read, add, update, and delete data. We work with SQLite databases using Python and visualize the information with the Matplotlib library.

**How the Program Works:**
At the beginning of the program, all phones manufactured by **Nokia** are retrieved and displayed. The user can then enter information about a new phone and add it to the database. The program also allows the user to update the **form factor** of a specific model and delete another model. Each operation is recorded in the database.

**Data Visualization:**
The program generates graphical charts to show the number of phones in the database for each manufacturer. It uses a **bar chart, pie chart, and scatter plot** to visualize the data.

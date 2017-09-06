Create Table vendingai
        id SERIAL PRIMARY KEY,
        type VARCHAR(255) NOT NULL,
        brand VARCHAR(255) NOT NULL,
        cost INTEGER NOT NULL

        Insert INTO vendingai (type, brand, cost, quantity) VALUES ('candy','snickers', 2, 10);

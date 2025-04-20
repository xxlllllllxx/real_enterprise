# ROADMAP

## INVENTORY MANAGEMENT 

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; OFFICE 2

    - DAILY INVENTORY 

        - IN (RAW INVENTORY)
            - LAPTOP
                - By Storage
                - By Brand
            - PC Parts
                - System Unit
                - Monitor
            - Add Ons
                - Mobile Phone
                - Boxes
                - Cables
                - Etc ...
            - Printers
                - By Model

        - OUT (TO OFFICE 1)
            - LAPTOP
                - WINDOWS
                - Chrome OS
            - PC SET
                - Monitor, System Unit, Cables, Mouse, Keyboard
            - Laptop Freebies SET
                - 8 Freebies Set - 8 from Add Ons
                - 1 Freebie - Mobile Phone or Helmet
                - Printer Set
            - Add Ons
                - Mobile Phone
                - Boxes
            - Printers

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; OFFICE 1

    - DAILY INVENTORY 
    
        - IN (FROM OFFICE 2)
            - LAPTOP
            - PC SET 
            - Freebies SET
            - Printers

        - OUT (SALES)
            - Laptop + Freebies SET
            - Laptop + Add Ons (Add Cost) + Freebies SET
            - PC SET + Freebies SET

# FOLDER STRUCTURE
    - base
        - base_inventory
            - _TBL_INVENTORY
                - TYPE
                    - LAPTOP
                    - PC PARTS
                    - Add Ons
                    - Printers
            - _TBL_FREEBIES
                - NAME
                - DETAILS (CATALOG)
                    - (FROM ADD ONS LIST WITH 0 PRICE)
            - _TBL_ADD_ONS
                - NAME
                - ADD ON PRICE
    
    - office 2
        - DAILY INVENTORY FOR LAPTOP AND PC
        - DAILY INVENTORY FOR FREEBIES AND ADD ONS

    - office 1
        - DAILY INVENTORY FROM office 2

        - DAILY SALES FOR WALK IN
        - DAILY SALES FOR LALAMOVE
        - DAILY SALES FOR LBC

    - reports
        - DAILY STOCKS
        - DAILY INVENTORY/SALES
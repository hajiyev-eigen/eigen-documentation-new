---
title: Logbook Configuration
description: A guide to using calculations in Ingenuity for data transformation and analysis.
sidebar:
    order: 2
---

Ingenuity Logbook module enables creation of sub-Logbooks. Sub-Logbooks enable recording data using custom forms different from the main Logbook but recorded withing the main Logbook instance.

## 3.1	Creating Logbook or Sub-Logbook instance

From the side menu, click Logbooks/Settings.

Image27

Then click Add New button

Image28

In the ‘Add New Logbook’ page, specify the Display Name, ID, Main log type, then click the Add button:

Image29

#### Display Name

Enter the Logbook instance name. This name will be displayed on the Logbook page and the menus. If an instance has associated sub-Logbooks it will appear as selection in Main Log Type.

#### ID

By default, ID is constructed from Display Name and spaces are replaced with dashes. This can be overwritten by the user.

#### Main Log Type

If the instance is a main Logbook this is set to the Display Name – Default. If however, the instance is a sub-Logbook of another Logbook instance then select the parent main Logbook from the dropdown.

Image30

#### Tags

If the instance is a sub-Logbook enter the reference Tag. The tag will be exposed as the field selection in the main Logbook

Image31

## 3.2	Configuring Data Entry Fields 

When a new instance is created it appears in the list of Logbooks. To configure Logbook, press the Edit button.

Image32

The following page shows the key parameters and default Layout

Image33

### 3.2.1	Standard Fields

A new instance of a Logbook has the following fields available by the default:

**Comments**

Users can enter the free-hand comments. Press ‘Enter’ to start a new line.

**Date and time**

Pick date and time from the calendar or type manually.

**Tags**

Enter relevant tag(s). The tags enable the filtering of Logbook entries. 

**Author**

The user id is automatically logged when a user creates an entry. The Author field is also the default filter field.

Image34

Image35

### 3.2.2	Creating New Custom Fields

Once a Logbook instance is created custom fields can be added to the set of the standard fields. 

Image36

To add new field, click Edit on the Logbook instance, then within Layout area click + Create New Field.

The required attributes for all fields are as follows:

***Label***

Image37

***Name of Field***

Image38

### 3.2.3	Select field

The ‘Select’ field option enables to create dropdown selection with specific entries.

Image39

To configure the selection, enter the selection items into ‘Dropdown Options’ field:

***Dropdown Options***

Press Enter after each entry.

Image40

***Can the user select multiple options?***

If user can select multiple options tick ‘Yes, multiselect’.
If user can only select single option tick ‘No, single select’.

Image41

***Visualization Type***

Dropdown – used typically for larger number of selections.

Radio Buttons – used typically for smaller number of selections

Image42

***Use this field as filter***

If ticked, the selection filed will be used a filter for selecting only the entries that match the criteria.

***Preview***

Use Preview to preview the appearance of the select field in the data entry form or as a filter before hitting Save button.

Image43

### 3.2.4	Text Field

The ‘Text’ field enables users to enter text entry into the Logbook record. Note, the standard field ‘Comment’ uses the Text Field.

Image44

No additional configuration is required, other than the standard *Label* and *Name of Field*.

3.2.5	Number

The ‘Number’ field users to enter numeric data into the Logbook record. The numeric data entries are treated as time-series data so it can be used with widgets such as Ingenuity chart, Ingenuity table, current value etc.  

Image45

No additional configuration is required, other than the standard *Label* and *Name of Field*.

### 3.2.6	Check Box

The ‘Checkbox’ field enables users to tick checkboxes when Yes or No answer is required in questionnaire type of log e.g. in inspection checklist.

Image46

*In addition to the standard Label and Name of Field, the Description string can be configured.*

Image47

### 3.2.7	Time-based Value

The ‘Time-based Value’ enables users to enter the timestamp data format entry into a Logbook record. Note that this is not the same as the Logbook record timestamp.

Image48

In addition to the standard *Label* and *Name of Field*, the *Create options with time ranges* should be used to create entries. Press Add Option to create new entry. 

Image49

The Logbook configuration opens in Edit Logbook form. Follow steps in [configuring data entry fields](#32configuring-data-entry-fields) to edit Logbook parameters.


Developed the code challenge in below online IDE
https://codesandbox.io/s/hardcore-dawn-ol5zi


Developed React smart dropdown component

parent Dropdown component has below props


1. user of type boolean

    which tells the dropdown to ADD & SELECT functionality if dropdown has no country
    
2. limit of type number

    which tells the dropdown to limit number of countries in initial render and show remaining as +more
    
3. onSelectItem of type event

    which emites the selected item in dropdown (if user logged in which emites the Add and selected country if required)
    
    
Child components

SEARCH COMPONENT:

1.Search component is presentational component and generated "onChange" event for user types something




LIST COMPONENT:

List compoent is used to generate the dynamic list based on input data

props: 
1. data of type Array of strings to render the country list
2. limit of type number which used to display dropdown countries
3. onSelect event to emit the selected dropdown item
4. onCLickAdd event to emit the add and selected received query
5. user of type boolean to enable Add and select functionality






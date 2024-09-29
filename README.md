# Kanban Board Assignment

## **Overview**
This project is a Kanban board application built with **ReactJS** that dynamically fetches data from an API and organizes tasks in a Kanban-style layout. The board provides three grouping options: by **Status**, **User**, and **Priority**, and allows sorting by **Priority** and **Title**.

## **Live Demo**
[https://quiksell-eight.vercel.app/]()

## **Features**
- **Grouping:** Users can group tasks by **Status**, **User**, or **Priority**.
- **Sorting:** Tasks can be sorted in **Descending Priority** or **Ascending Title** order.
- **Dynamic Fetching:** Data is dynamically fetched from the provided API.
- **State Persistence:** The application saves user preferences for grouping and sorting even after page reload.
- **Responsive Design:** The layout is fully responsive and adjusts based on the screen size.
- **Pure CSS:** Styled without any external CSS libraries (Bootstrap, Tailwind, etc.), ensuring a custom and clean UI.


### **API Information**
The application interacts with the following API to fetch task data:

```
https://api.quicksell.co/v1/internal/frontend-assignment
```

## **Responsive Design**
The application is fully responsive and adapts to different screen sizes using CSS Grid and Flexbox for layout.

## **How to Use**
1. **Select Grouping Option:** Use the dropdown to group tasks by **Status**, **User**, or **Priority**.
2. **Sort Tasks:** Sort tasks either by **Priority** (descending) or **Title** (ascending).
3. **Persist Settings:** The app automatically saves your grouping and sorting preferences even after reloading the page.

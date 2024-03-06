# Active Users Component

- component path :- /src/components/Dashboard/ActiveUsers/index.tsx
- Active user component is a pie chart component which will show the active user (who complete the onboarding) and the user which does not complete the onboarding yet.

### Flow from Steps

- Step 1 :- We get the data from the GET_DASHBOARD which contains the query using the useQuery hooks which make request to the backend and load the data.
- Step 2 :- Until the data does not loader will appear
- Step 3 :- Get the active user
- Step 4 :- Get the total using reduce 
> Reduce is the javascript function used in the array to return single value.
- Step 5 :- Create the graph data
> Using map we add the label for the pie chart.
- Step 6 :- Create and return the pie chart data

## Total Events Over Time Component

- component path :- /src/components/Dashboard/TotalEventsOverTime/index.tsx

!> Don't know what the Total events over time component area chart represents ?

### Flow from Steps

- Step 1 :- We get the data from the GET_DASHBOARD which contains the query using the useQuery hooks which make request to the backend and load the data.
> The "GET_DASHBOARD" includes the GraphQL schema, which comprises a nested hash of query names and keys.
- Step 2 :- Until the data does not loader will appear
- Step 3 :- Create the graph data for the area chart graph.
> Using map we add the label for the area chart graph.
- Step 4 :- Create and return the area chart data.

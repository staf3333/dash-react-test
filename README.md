# dash-react-test

## Testing Dash

At first, I thought that I could use custom Plotly Dash components in my Adilyze data visualization app. But after further consideration, I don't think this makes sense:

- Dash itself is built in React! It seems as though it's a way to make dashboard (which are at heart web apps) easier for Python developers who don't necessarily know JS and frontend frameworks
- Why create custom Dash components when I can just use JS data visualization libraries to do the same thing. I'm not a web dev noob (somewhat)

## Moving to D3

After further research, I think it makes sense to use D3 instead of Dash (and ChartJS, which I was using before). Though D3 is a bit harder to work with than ChartJS, it allows for more customizability, which I think I'll want.

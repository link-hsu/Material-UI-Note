# Material-UI
- [Course-Link](https://www.youtube.com/playlist?list=PL4cUxeGkcC9gjxLvV4VEkZ6H6H4yWuS58 "material-ui")
- Install - see [docs](https://mui.com/material-ui/getting-started/installation/)
  ```npm install @mui/material @emotion/react @emotion/styled```  
  ```npm install @mui/material @mui/styled-engine-sc styled-components```  
- Typography - see [docs](https://mui.com/material-ui/api/typography/)
  - variant - styling of HTML element
  - component - rendered what element in dom
  - nowrap
  - gutterbottom
- Button - see [docs](https://mui.com/material-ui/react-button/)
  - props
    - variant - text(default) | contained | outlined
    - disabled
    - onClick
    - startIcon
    - endIcon
- How to use icon? [material-icons](https://mui.com/material-ui/material-icons/)
  - ```npm install @mui/icons-material```
  - ```import WindPowerIcon from '@mui/icons-material/WindPower';```
  - props:
    - color
    - fontSize
    - sx
- makeStyles Hook - depredicated ** Use [MUI-System](https://mui.com/system/getting-started/the-sx-prop/) as replacement 
- [Default Theme Objet](https://mui.com/material-ui/customization/default-theme/)
  - [Customizing Theme](https://mui.com/material-ui/customization/theming/)
  - ~~~ js
    const theme = createTheme({
        palette: {
          primary: {
            main: '#fefefe',
          },
          secondary: purple
        },
        typography: {
          fontFamily: 'Quicksand',
          fontWeightLight: 400,
          fontWeightRegular: 500,
          fontWeightMedium: 600,
          fontWeightBold: 700,
        },
    });
    <ThemeProvider theme={theme}></ThemeProvider>
    ~~~
- [TextField](https://mui.com/material-ui/react-text-field/ "Link here")
  - api - [Link](https://mui.com/material-ui/api/text-field/)
  - variant - 'outlined'(default) | 'standard' 'filled' |
  - label
  - fullWidth
  - required
  - ```multiline```  
    ```rows={4}```
  - onChange
  - error={true}
- [Radio Group](https://mui.com/material-ui/react-radio-button/ "Link here")
  - ~~~ jsx
    <FormControl>
      <FormLabel id="demo-radio-buttons-group-label">Gender</FormLabel>
      <RadioGroup
        aria-labelledby="demo-radio-buttons-group-label"
        defaultValue="female"
        name="radio-buttons-group"
      >
        <FormControlLabel value="female" control={<Radio />} label="Female" />
        <FormControlLabel value="male" control={<Radio />} label="Male" />
        <FormControlLabel value="other" control={<Radio />} label="Other" />
      </RadioGroup>
    </FormControl>
    ~~~
- [JSON server](https://andy6804tw.github.io/2018/02/01/json-server-intro/#put-%E6%9B%B4%E6%96%B0%E5%AE%8C%E6%95%B4%E8%B3%87%E6%96%99 "Link here")
  - ```npm install -g json-server```  
    ```json-server --watch data/db.json --port 8000```
- [Grid System](https://mui.com/system/react-grid/ "Link here")
  - [Grid-api](https://mui.com/system/api/grid/)
  - [CSS-grid](https://mui.com/system/grid/)
- [Card](https://mui.com/material-ui/react-card/ "Link here")
- [Drawer](https://mui.com/material-ui/react-drawer/ "Link here")



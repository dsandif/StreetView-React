# StreetView-React
A stateful Google streetview component for older versions of React.js

**Usage**
```javascript
<StreetView
  address={address}
  zip={String(zip)}
  APIkey={YOUR_MAPS_API_KEY}
  streetView={true}
  zoomLevel={15} />
  
  
  StreetView.propTypes = {
    APIkey: PropTypes.string.isRequired,
    mapStyle: PropTypes.any,
    textStyle: PropTypes.object,
    address: PropTypes.string.isRequired,
    zip: PropTypes.string,
    streetView: PropTypes.bool,
    zoomLevel: PropTypes.number,
    streetViewZoom: PropTypes.number,
    defaultText: PropTypes.string,
    errorText: PropTypes.string,
}
```

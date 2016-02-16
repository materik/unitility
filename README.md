# Unitility

Easy to use and understand pod for storing, formatting and converting units of
different measurements.

## Install

```bash
pod install 'Unitility'
```

## Example

```objective-c
#import <Unitility/Length.h>

Meter *m = [Length meter:5.2f];
Foot *f = [m convertToFoot];
NSLog(@"%@", [f formatted]); // 17.06 ft
```

## Units

### Length

- Centimeter
- Foot
- Inch
- Meter

### Temperature

- Celcius
- Farenheit
- Kelvin

### Weight

- Gram
- Kilogram
- Pound
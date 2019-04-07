# fips-rapidjson

fipsified rapidjson (https://github.com/Tencent/rapidjson)

fips build system: https://github.com/floooh/fips

### Changes

- Added extra parentheses around calls to __std::numeric_limits<T>::max__ and __std::numeric_limits<T>::min__. 
This fixes an issue with _min_ and _max_ macro definitions in _windef.h_ (visual studio builds).

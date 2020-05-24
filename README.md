<a name="root"></a>
# osiota application debug-output

*Osiota* is a software platform capable of running *distributed IoT applications* written in JavaScript to enable any kind of IoT tasks. See [osiota](https://github.com/osiota/osiota).

## Configuration: debug-output


This application can be used to output a string to the console for debugging purposes.

**Properties**

|Name|Description|Type|
|----|-----------|----|
|text|Debug output text<br/>|string|


**Example**

```json
{
    "text": "Hello World!"
}
```


## How to setup

Add a configuration object for this application, see [osiota configuration](https://github.com/osiota/osiota/blob/master/doc/configuration.md):

```json
{
    "name": "debug-output",
    "config": CONFIG
}
```

## License

Osiota and this application are released under the MIT license.

Please note that this project is released with a [Contributor Code of Conduct](https://github.com/osiota/osiota/blob/master/CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.

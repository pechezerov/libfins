# Libfins API Reference

### `finslib_message_read( sys, msgdata, msg_mask );`

### Parameters

| Parameter | Type | Description |
| :--- | :--- | :--- |
|**`sys`**|`struct fins_sys_tp *`|A pointer to a structure with the FINS context|
|**`msgdata`**|`struct fins_msgdata_tp *`|Pointer to the buffer where the message information should be stored|
|**`msg_mask`**|`uint8_t`|Bit mask identifying the messages to be retrieved|

### Return Value

| Type | Description |
| :--- | :--- |
|`int`|A return value from the list [`FINS_RETVAL_...`](fins_retval.md) indicating the result of the query|

### Description

### See Also

* [`FINS_RETVAL...`](fins_retval.md) &ndash; Libfins function return code list
* [`FINS_MSG...`](fins_msg.md) &ndash; Message bit mask list
* [`finslib_error_clear();`](finslib_error_clear.md)
* [`finslib_error_clear_all();`](finslib_error_clear_all.md)
* [`finslib_error_clear_current();`](finslib_error_clear_current.md)
* [`finslib_error_clear_fal();`](finslib_error_clear_fal.md)
* [`finslib_error_clear_fals();`](finslib_error_clear_fals.md)
* [`finslib_error_log_clear();`](finslib_error_log_clear.md)
* [`finslib_error_log_read();`](finslib_error_log_read.md)
* [`finslib_message_clear();`](finslib_message_read.md)
* [`finslib_message_fal_fals_read();`](finslib_message_fal_fals_read.md)

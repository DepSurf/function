# Function: <code>__bpf_trace_smbus_reply</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __bpf_trace_smbus_reply(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/trace/events/smbus.h:137
Inline: False
```
**Symbols:**

```
ffffffff817d78a0-ffffffff817d78c2: __bpf_trace_smbus_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_smbus_reply(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/trace/events/smbus.h:137
Inline: False
```
**Symbols:**

```
ffffffff817fea00-ffffffff817fea22: __bpf_trace_smbus_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_smbus_reply(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8183e8b0)
Location: include/trace/events/smbus.h:133
Inline: False
```
**Symbols:**

```
ffffffff8183e8b0-ffffffff8183e8d8: __bpf_trace_smbus_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_smbus_reply(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81870250)
Location: include/trace/events/smbus.h:133
Inline: False
```
**Symbols:**

```
ffffffff81870250-ffffffff81870278: __bpf_trace_smbus_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_smbus_reply(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff819441a0)
Location: include/trace/events/smbus.h:133
Inline: False
```
**Symbols:**

```
ffffffff819441a0-ffffffff819441c8: __bpf_trace_smbus_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_smbus_reply(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8194a220)
Location: include/trace/events/smbus.h:133
Inline: False
```
**Symbols:**

```
ffffffff8194a220-ffffffff8194a248: __bpf_trace_smbus_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_smbus_reply(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8192daf0)
Location: include/trace/events/smbus.h:133
Inline: False
```
**Symbols:**

```
ffffffff8192daf0-ffffffff8192db18: __bpf_trace_smbus_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_smbus_reply(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff819d0d00)
Location: include/trace/events/smbus.h:133
Inline: False
```
**Symbols:**

```
ffffffff819d0d00-ffffffff819d0d28: __bpf_trace_smbus_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_smbus_reply(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81b33140)
Location: include/trace/events/smbus.h:133
Inline: False
```
**Symbols:**

```
ffffffff81b33140-ffffffff81b3317c: __bpf_trace_smbus_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_smbus_reply(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc7680)
Location: include/trace/events/smbus.h:133
Inline: False
```
**Symbols:**

```
ffffffff81cc7680-ffffffff81cc76bc: __bpf_trace_smbus_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_smbus_reply(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d2f3b0)
Location: include/trace/events/smbus.h:133
Inline: False
```
**Symbols:**

```
ffffffff81d2f3b0-ffffffff81d2f3ec: __bpf_trace_smbus_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_smbus_reply(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de5360)
Location: include/trace/events/smbus.h:133
Inline: False
```
**Symbols:**

```
ffffffff81de5360-ffffffff81de539c: __bpf_trace_smbus_reply (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __bpf_trace_smbus_reply(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffff800010ab33c8)
Location: include/trace/events/smbus.h:133
Inline: False
```
**Symbols:**

```
ffff800010ab33c8-ffff800010ab3400: __bpf_trace_smbus_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_smbus_reply(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c0b94ea4)
Location: include/trace/events/smbus.h:133
Inline: False
```
**Symbols:**

```
c0b94ea4-c0b94f18: __bpf_trace_smbus_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_smbus_reply(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c000000000b976d0)
Location: include/trace/events/smbus.h:133
Inline: False
```
**Symbols:**

```
c000000000b976d0-c000000000b97708: __bpf_trace_smbus_reply (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_smbus_reply(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff818643e0)
Location: include/trace/events/smbus.h:133
Inline: False
```
**Symbols:**

```
ffffffff818643e0-ffffffff81864408: __bpf_trace_smbus_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_smbus_reply(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8187f640)
Location: include/trace/events/smbus.h:133
Inline: False
```
**Symbols:**

```
ffffffff8187f640-ffffffff8187f668: __bpf_trace_smbus_reply (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int res</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>

# Function: <code>__bpf_trace_smbus_write</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_smbus_write(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817d6600)
Location: include/trace/events/smbus.h:27
Inline: True
```
**Symbols:**

```
ffffffff817d6600-ffffffff817d6622: __bpf_trace_smbus_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_smbus_write(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817fd730)
Location: include/trace/events/smbus.h:27
Inline: True
```
**Symbols:**

```
ffffffff817fd730-ffffffff817fd752: __bpf_trace_smbus_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_smbus_write(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8183e830)
Location: include/trace/events/smbus.h:23
Inline: False
```
**Symbols:**

```
ffffffff8183e830-ffffffff8183e852: __bpf_trace_smbus_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_smbus_write(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff818701d0)
Location: include/trace/events/smbus.h:23
Inline: False
```
**Symbols:**

```
ffffffff818701d0-ffffffff818701f2: __bpf_trace_smbus_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_smbus_write(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81944120)
Location: include/trace/events/smbus.h:23
Inline: False
```
**Symbols:**

```
ffffffff81944120-ffffffff81944142: __bpf_trace_smbus_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_smbus_write(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8194a1a0)
Location: include/trace/events/smbus.h:23
Inline: False
```
**Symbols:**

```
ffffffff8194a1a0-ffffffff8194a1c2: __bpf_trace_smbus_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_smbus_write(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8192da70)
Location: include/trace/events/smbus.h:23
Inline: False
```
**Symbols:**

```
ffffffff8192da70-ffffffff8192da92: __bpf_trace_smbus_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_smbus_write(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff819d0c80)
Location: include/trace/events/smbus.h:23
Inline: False
```
**Symbols:**

```
ffffffff819d0c80-ffffffff819d0ca2: __bpf_trace_smbus_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_smbus_write(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81b33080)
Location: include/trace/events/smbus.h:23
Inline: False
```
**Symbols:**

```
ffffffff81b33080-ffffffff81b330b6: __bpf_trace_smbus_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_smbus_write(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc7590)
Location: include/trace/events/smbus.h:23
Inline: False
```
**Symbols:**

```
ffffffff81cc7590-ffffffff81cc75c6: __bpf_trace_smbus_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_smbus_write(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d2f2c0)
Location: include/trace/events/smbus.h:23
Inline: False
```
**Symbols:**

```
ffffffff81d2f2c0-ffffffff81d2f2f6: __bpf_trace_smbus_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_smbus_write(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de5270)
Location: include/trace/events/smbus.h:23
Inline: False
```
**Symbols:**

```
ffffffff81de5270-ffffffff81de52a6: __bpf_trace_smbus_write (STB_LOCAL)
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
void __bpf_trace_smbus_write(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffff800010ab3348)
Location: include/trace/events/smbus.h:23
Inline: False
```
**Symbols:**

```
ffff800010ab3348-ffff800010ab3370: __bpf_trace_smbus_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_smbus_write(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c0b94d78)
Location: include/trace/events/smbus.h:23
Inline: False
```
**Symbols:**

```
c0b94d78-c0b94de0: __bpf_trace_smbus_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_smbus_write(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c000000000b97630)
Location: include/trace/events/smbus.h:23
Inline: False
```
**Symbols:**

```
c000000000b97630-c000000000b97660: __bpf_trace_smbus_write (STB_LOCAL)
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
void __bpf_trace_smbus_write(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81864360)
Location: include/trace/events/smbus.h:23
Inline: False
```
**Symbols:**

```
ffffffff81864360-ffffffff81864382: __bpf_trace_smbus_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_smbus_write(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8187f5c0)
Location: include/trace/events/smbus.h:23
Inline: False
```
**Symbols:**

```
ffffffff8187f5c0-ffffffff8187f5e2: __bpf_trace_smbus_write (STB_LOCAL)
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
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

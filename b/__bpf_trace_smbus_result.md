# Function: <code>__bpf_trace_smbus_result</code>

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
void __bpf_trace_smbus_result(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817d6630)
Location: include/trace/events/smbus.h:203
Inline: False
```
**Symbols:**

```
ffffffff817d6630-ffffffff817d6653: __bpf_trace_smbus_result (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_smbus_result(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817fd760)
Location: include/trace/events/smbus.h:203
Inline: False
```
**Symbols:**

```
ffffffff817fd760-ffffffff817fd783: __bpf_trace_smbus_result (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_smbus_result(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8183e860)
Location: include/trace/events/smbus.h:199
Inline: False
```
**Symbols:**

```
ffffffff8183e860-ffffffff8183e883: __bpf_trace_smbus_result (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_smbus_result(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81870200)
Location: include/trace/events/smbus.h:199
Inline: False
```
**Symbols:**

```
ffffffff81870200-ffffffff81870223: __bpf_trace_smbus_result (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_smbus_result(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81944150)
Location: include/trace/events/smbus.h:199
Inline: False
```
**Symbols:**

```
ffffffff81944150-ffffffff81944173: __bpf_trace_smbus_result (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_smbus_result(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8194a1d0)
Location: include/trace/events/smbus.h:199
Inline: False
```
**Symbols:**

```
ffffffff8194a1d0-ffffffff8194a1f3: __bpf_trace_smbus_result (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_smbus_result(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8192daa0)
Location: include/trace/events/smbus.h:199
Inline: False
```
**Symbols:**

```
ffffffff8192daa0-ffffffff8192dac3: __bpf_trace_smbus_result (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_smbus_result(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff819d0cb0)
Location: include/trace/events/smbus.h:199
Inline: False
```
**Symbols:**

```
ffffffff819d0cb0-ffffffff819d0cd3: __bpf_trace_smbus_result (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_smbus_result(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81b330c0)
Location: include/trace/events/smbus.h:199
Inline: False
```
**Symbols:**

```
ffffffff81b330c0-ffffffff81b330f7: __bpf_trace_smbus_result (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_smbus_result(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc75e0)
Location: include/trace/events/smbus.h:199
Inline: False
```
**Symbols:**

```
ffffffff81cc75e0-ffffffff81cc7617: __bpf_trace_smbus_result (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_smbus_result(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d2f310)
Location: include/trace/events/smbus.h:199
Inline: False
```
**Symbols:**

```
ffffffff81d2f310-ffffffff81d2f347: __bpf_trace_smbus_result (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_smbus_result(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de52c0)
Location: include/trace/events/smbus.h:199
Inline: False
```
**Symbols:**

```
ffffffff81de52c0-ffffffff81de52f7: __bpf_trace_smbus_result (STB_LOCAL)
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
void __bpf_trace_smbus_result(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffff800010ab3370)
Location: include/trace/events/smbus.h:199
Inline: False
```
**Symbols:**

```
ffff800010ab3370-ffff800010ab339c: __bpf_trace_smbus_result (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_smbus_result(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c0b94de0)
Location: include/trace/events/smbus.h:199
Inline: False
```
**Symbols:**

```
c0b94de0-c0b94e48: __bpf_trace_smbus_result (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_smbus_result(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c000000000b97660)
Location: include/trace/events/smbus.h:199
Inline: False
```
**Symbols:**

```
c000000000b97660-c000000000b97694: __bpf_trace_smbus_result (STB_LOCAL)
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
void __bpf_trace_smbus_result(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81864390)
Location: include/trace/events/smbus.h:199
Inline: False
```
**Symbols:**

```
ffffffff81864390-ffffffff818643b3: __bpf_trace_smbus_result (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_smbus_result(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8187f5f0)
Location: include/trace/events/smbus.h:199
Inline: False
```
**Symbols:**

```
ffffffff8187f5f0-ffffffff8187f613: __bpf_trace_smbus_result (STB_LOCAL)
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

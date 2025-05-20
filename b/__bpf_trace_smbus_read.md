# Function: <code>__bpf_trace_smbus_read</code>

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
void __bpf_trace_smbus_read(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817d6660)
Location: include/trace/events/smbus.h:95
Inline: False
```
**Symbols:**

```
ffffffff817d6660-ffffffff817d667e: __bpf_trace_smbus_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_smbus_read(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817fd790)
Location: include/trace/events/smbus.h:95
Inline: False
```
**Symbols:**

```
ffffffff817fd790-ffffffff817fd7ae: __bpf_trace_smbus_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_smbus_read(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8183e890)
Location: include/trace/events/smbus.h:91
Inline: False
```
**Symbols:**

```
ffffffff8183e890-ffffffff8183e8ae: __bpf_trace_smbus_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_smbus_read(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81870230)
Location: include/trace/events/smbus.h:91
Inline: False
```
**Symbols:**

```
ffffffff81870230-ffffffff8187024e: __bpf_trace_smbus_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_smbus_read(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81944180)
Location: include/trace/events/smbus.h:91
Inline: False
```
**Symbols:**

```
ffffffff81944180-ffffffff8194419e: __bpf_trace_smbus_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_smbus_read(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8194a200)
Location: include/trace/events/smbus.h:91
Inline: False
```
**Symbols:**

```
ffffffff8194a200-ffffffff8194a21e: __bpf_trace_smbus_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_smbus_read(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8192dad0)
Location: include/trace/events/smbus.h:91
Inline: False
```
**Symbols:**

```
ffffffff8192dad0-ffffffff8192daee: __bpf_trace_smbus_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_smbus_read(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff819d0ce0)
Location: include/trace/events/smbus.h:91
Inline: False
```
**Symbols:**

```
ffffffff819d0ce0-ffffffff819d0cfe: __bpf_trace_smbus_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_smbus_read(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81b33100)
Location: include/trace/events/smbus.h:91
Inline: False
```
**Symbols:**

```
ffffffff81b33100-ffffffff81b33132: __bpf_trace_smbus_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_smbus_read(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc7630)
Location: include/trace/events/smbus.h:91
Inline: False
```
**Symbols:**

```
ffffffff81cc7630-ffffffff81cc7662: __bpf_trace_smbus_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_smbus_read(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d2f360)
Location: include/trace/events/smbus.h:91
Inline: False
```
**Symbols:**

```
ffffffff81d2f360-ffffffff81d2f392: __bpf_trace_smbus_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_smbus_read(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de5310)
Location: include/trace/events/smbus.h:91
Inline: False
```
**Symbols:**

```
ffffffff81de5310-ffffffff81de5342: __bpf_trace_smbus_read (STB_LOCAL)
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
void __bpf_trace_smbus_read(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffff800010ab33a0)
Location: include/trace/events/smbus.h:91
Inline: False
```
**Symbols:**

```
ffff800010ab33a0-ffff800010ab33c8: __bpf_trace_smbus_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_smbus_read(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c0b94e48)
Location: include/trace/events/smbus.h:91
Inline: False
```
**Symbols:**

```
c0b94e48-c0b94ea4: __bpf_trace_smbus_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_smbus_read(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c000000000b976a0)
Location: include/trace/events/smbus.h:91
Inline: False
```
**Symbols:**

```
c000000000b976a0-c000000000b976d0: __bpf_trace_smbus_read (STB_LOCAL)
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
void __bpf_trace_smbus_read(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff818643c0)
Location: include/trace/events/smbus.h:91
Inline: False
```
**Symbols:**

```
ffffffff818643c0-ffffffff818643de: __bpf_trace_smbus_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_smbus_read(void *__data, const struct i2c_adapter *adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8187f620)
Location: include/trace/events/smbus.h:91
Inline: False
```
**Symbols:**

```
ffffffff8187f620-ffffffff8187f63e: __bpf_trace_smbus_read (STB_LOCAL)
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

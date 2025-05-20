# Function: <code>__bpf_trace_i2c_write</code>

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
void __bpf_trace_i2c_write(void *__data, const struct i2c_adapter *adap, const struct i2c_msg *msg, int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817d2900)
Location: include/trace/events/i2c.h:29
Inline: True
```
**Symbols:**

```
ffffffff817d2900-ffffffff817d290d: __bpf_trace_i2c_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_i2c_write(void *__data, const struct i2c_adapter *adap, const struct i2c_msg *msg, int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817f9a60)
Location: include/trace/events/i2c.h:29
Inline: True
```
**Symbols:**

```
ffffffff817f9a60-ffffffff817f9a6d: __bpf_trace_i2c_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_i2c_write(void *__data, const struct i2c_adapter *adap, const struct i2c_msg *msg, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8183a760)
Location: include/trace/events/i2c.h:25
Inline: False
```
**Symbols:**

```
ffffffff8183a760-ffffffff8183a76d: __bpf_trace_i2c_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_i2c_write(void *__data, const struct i2c_adapter *adap, const struct i2c_msg *msg, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8186c0d0)
Location: include/trace/events/i2c.h:25
Inline: False
```
**Symbols:**

```
ffffffff8186c0d0-ffffffff8186c0dd: __bpf_trace_i2c_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_i2c_write(void *__data, const struct i2c_adapter *adap, const struct i2c_msg *msg, int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8193fe10)
Location: include/trace/events/i2c.h:25
Inline: True
```
**Symbols:**

```
ffffffff8193fe10-ffffffff8193fe1d: __bpf_trace_i2c_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_i2c_write(void *__data, const struct i2c_adapter *adap, const struct i2c_msg *msg, int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81945fa0)
Location: include/trace/events/i2c.h:25
Inline: True
```
**Symbols:**

```
ffffffff81945fa0-ffffffff81945fad: __bpf_trace_i2c_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_i2c_write(void *__data, const struct i2c_adapter *adap, const struct i2c_msg *msg, int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81929780)
Location: include/trace/events/i2c.h:25
Inline: True
```
**Symbols:**

```
ffffffff81929780-ffffffff8192978d: __bpf_trace_i2c_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_i2c_write(void *__data, const struct i2c_adapter *adap, const struct i2c_msg *msg, int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff819cc8d0)
Location: include/trace/events/i2c.h:25
Inline: True
```
**Symbols:**

```
ffffffff819cc8d0-ffffffff819cc8dd: __bpf_trace_i2c_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_i2c_write(void *__data, const struct i2c_adapter *adap, const struct i2c_msg *msg, int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81b2e4a0)
Location: include/trace/events/i2c.h:25
Inline: True
```
**Symbols:**

```
ffffffff81b2e4a0-ffffffff81b2e4b9: __bpf_trace_i2c_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_i2c_write(void *__data, const struct i2c_adapter *adap, const struct i2c_msg *msg, int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81cc2170)
Location: include/trace/events/i2c.h:25
Inline: True
```
**Symbols:**

```
ffffffff81cc2170-ffffffff81cc2189: __bpf_trace_i2c_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_i2c_write(void *__data, const struct i2c_adapter *adap, const struct i2c_msg *msg, int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81d29b80)
Location: include/trace/events/i2c.h:25
Inline: True
```
**Symbols:**

```
ffffffff81d29b80-ffffffff81d29b99: __bpf_trace_i2c_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_i2c_write(void *__data, const struct i2c_adapter *adap, const struct i2c_msg *msg, int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81ddfa40)
Location: include/trace/events/i2c.h:25
Inline: True
```
**Symbols:**

```
ffffffff81ddfa40-ffffffff81ddfa59: __bpf_trace_i2c_write (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_i2c_write(void *__data, const struct i2c_adapter *adap, const struct i2c_msg *msg, int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffff800010aaeb08)
Location: include/trace/events/i2c.h:25
Inline: True
```
**Symbols:**

```
ffff800010aaeb08-ffff800010aaeb20: __bpf_trace_i2c_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_i2c_write(void *__data, const struct i2c_adapter *adap, const struct i2c_msg *msg, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c0b908b0)
Location: include/trace/events/i2c.h:25
Inline: False
```
**Symbols:**

```
c0b908b0-c0b908e8: __bpf_trace_i2c_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_i2c_write(void *__data, const struct i2c_adapter *adap, const struct i2c_msg *msg, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c000000000b91460)
Location: include/trace/events/i2c.h:25
Inline: False
```
**Symbols:**

```
c000000000b91460-c000000000b91490: __bpf_trace_i2c_write (STB_LOCAL)
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
void __bpf_trace_i2c_write(void *__data, const struct i2c_adapter *adap, const struct i2c_msg *msg, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81860260)
Location: include/trace/events/i2c.h:25
Inline: False
```
**Symbols:**

```
ffffffff81860260-ffffffff8186026d: __bpf_trace_i2c_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_i2c_write(void *__data, const struct i2c_adapter *adap, const struct i2c_msg *msg, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8187b470)
Location: include/trace/events/i2c.h:25
Inline: False
```
**Symbols:**

```
ffffffff8187b470-ffffffff8187b47d: __bpf_trace_i2c_write (STB_LOCAL)
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

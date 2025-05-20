# Function: <code>__bpf_trace_add_device_randomness</code>

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
void __bpf_trace_add_device_randomness(void *__data, int bytes, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81645ba0)
Location: include/trace/events/random.h:11
Inline: True
```
**Symbols:**

```
ffffffff81645ba0-ffffffff81645bad: __bpf_trace_add_device_randomness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_add_device_randomness(void *__data, int bytes, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81663ea0)
Location: include/trace/events/random.h:11
Inline: True
```
**Symbols:**

```
ffffffff81663ea0-ffffffff81663ead: __bpf_trace_add_device_randomness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_add_device_randomness(void *__data, int bytes, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81699830)
Location: include/trace/events/random.h:11
Inline: False
```
**Symbols:**

```
ffffffff81699830-ffffffff8169983d: __bpf_trace_add_device_randomness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_add_device_randomness(void *__data, int bytes, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816bc440)
Location: include/trace/events/random.h:11
Inline: False
```
**Symbols:**

```
ffffffff816bc440-ffffffff816bc44d: __bpf_trace_add_device_randomness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_add_device_randomness(void *__data, int bytes, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff817707e0)
Location: include/trace/events/random.h:11
Inline: True
```
**Symbols:**

```
ffffffff817707e0-ffffffff817707ed: __bpf_trace_add_device_randomness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_add_device_randomness(void *__data, int bytes, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8178b840)
Location: include/trace/events/random.h:11
Inline: True
```
**Symbols:**

```
ffffffff8178b840-ffffffff8178b84d: __bpf_trace_add_device_randomness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_add_device_randomness(void *__data, int bytes, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8176eaa0)
Location: include/trace/events/random.h:11
Inline: True
```
**Symbols:**

```
ffffffff8176eaa0-ffffffff8176eaad: __bpf_trace_add_device_randomness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_add_device_randomness(void *__data, int bytes, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff817f4270)
Location: include/trace/events/random.h:11
Inline: True
```
**Symbols:**

```
ffffffff817f4270-ffffffff817f427d: __bpf_trace_add_device_randomness (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_add_device_randomness(void *__data, int bytes, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffff8000108ac310)
Location: include/trace/events/random.h:11
Inline: True
```
**Symbols:**

```
ffff8000108ac310-ffff8000108ac328: __bpf_trace_add_device_randomness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_add_device_randomness(void *__data, int bytes, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c09a91e8)
Location: include/trace/events/random.h:11
Inline: False
```
**Symbols:**

```
c09a91e8-c09a9210: __bpf_trace_add_device_randomness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_add_device_randomness(void *__data, int bytes, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c0000000009454c0)
Location: include/trace/events/random.h:11
Inline: False
```
**Symbols:**

```
c0000000009454c0-c0000000009454f0: __bpf_trace_add_device_randomness (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __bpf_trace_add_device_randomness(void *__data, int bytes, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81681ea0)
Location: include/trace/events/random.h:11
Inline: False
```
**Symbols:**

```
ffffffff81681ea0-ffffffff81681ead: __bpf_trace_add_device_randomness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_add_device_randomness(void *__data, int bytes, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8165fd20)
Location: include/trace/events/random.h:11
Inline: False
```
**Symbols:**

```
ffffffff8165fd20-ffffffff8165fd2d: __bpf_trace_add_device_randomness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_add_device_randomness(void *__data, int bytes, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816b0280)
Location: include/trace/events/random.h:11
Inline: False
```
**Symbols:**

```
ffffffff816b0280-ffffffff816b028d: __bpf_trace_add_device_randomness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_add_device_randomness(void *__data, int bytes, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816ca8e0)
Location: include/trace/events/random.h:11
Inline: False
```
**Symbols:**

```
ffffffff816ca8e0-ffffffff816ca8ed: __bpf_trace_add_device_randomness (STB_LOCAL)
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
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>

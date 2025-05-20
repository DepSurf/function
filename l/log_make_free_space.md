# Function: <code>log_make_free_space</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int log_make_free_space(u32 msg_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810d6c30)
Location: kernel/printk/printk.c:367
Inline: True
Direct callers:
  - kernel/printk/printk.c:log_store
  - kernel/printk/printk.c:log_store
```
**Symbols:**

```
ffffffff810d6c30-ffffffff810d6d08: log_make_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int log_make_free_space(u32 msg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810db420)
Location: kernel/printk/printk.c:473
Inline: False
Direct callers:
  - kernel/printk/printk.c:log_store
  - kernel/printk/printk.c:log_store
```
**Symbols:**

```
ffffffff810db420-ffffffff810db533: log_make_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int log_make_free_space(u32 msg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e1ef0)
Location: kernel/printk/printk.c:471
Inline: False
Direct callers:
  - kernel/printk/printk.c:log_store
  - kernel/printk/printk.c:log_store
```
**Symbols:**

```
ffffffff810e1ef0-ffffffff810e2003: log_make_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int log_make_free_space(u32 msg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e1050)
Location: kernel/printk/printk.c:520
Inline: False
Direct callers:
  - kernel/printk/printk.c:log_store
  - kernel/printk/printk.c:log_store
```
**Symbols:**

```
ffffffff810e1050-ffffffff810e11b1: log_make_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int log_make_free_space(u32 msg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e9300)
Location: kernel/printk/printk.c:520
Inline: False
Direct callers:
  - kernel/printk/printk.c:log_store
  - kernel/printk/printk.c:log_store
```
**Symbols:**

```
ffffffff810e9300-ffffffff810e9461: log_make_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int log_make_free_space(u32 msg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810f1640)
Location: kernel/printk/printk.c:524
Inline: False
Direct callers:
  - kernel/printk/printk.c:log_store
  - kernel/printk/printk.c:log_store
```
**Symbols:**

```
ffffffff810f1640-ffffffff810f173c: log_make_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int log_make_free_space(u32 msg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fccd0)
Location: kernel/printk/printk.c:520
Inline: False
Direct callers:
  - kernel/printk/printk.c:log_store
  - kernel/printk/printk.c:log_store
```
**Symbols:**

```
ffffffff810fccd0-ffffffff810fcdcc: log_make_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int log_make_free_space(u32 msg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811053c0)
Location: kernel/printk/printk.c:534
Inline: False
```
**Symbols:**

```
ffffffff811053c0-ffffffff811054bc: log_make_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int log_make_free_space(u32 msg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81111740)
Location: kernel/printk/printk.c:544
Inline: False
```
**Symbols:**

```
ffffffff81111740-ffffffff8111183c: log_make_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int log_make_free_space(u32 msg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111cde0)
Location: kernel/printk/printk.c:556
Inline: False
```
**Symbols:**

```
ffffffff8111cde0-ffffffff8111cedc: log_make_free_space (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int log_make_free_space(u32 msg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffff800010171c10)
Location: kernel/printk/printk.c:544
Inline: False
```
**Symbols:**

```
ffff800010171c10-ffff800010171d24: log_make_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int log_make_free_space(u32 msg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c03c4570)
Location: kernel/printk/printk.c:544
Inline: False
```
**Symbols:**

```
c03c4570-c03c46d4: log_make_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int log_make_free_space(u32 msg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c0000000001ca450)
Location: kernel/printk/printk.c:544
Inline: False
```
**Symbols:**

```
c0000000001ca450-c0000000001ca5c8: log_make_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int log_make_free_space(u32 msg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffe00010dec6)
Location: kernel/printk/printk.c:544
Inline: False
```
**Symbols:**

```
ffffffe00010dec6-ffffffe00010dfdc: log_make_free_space (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int log_make_free_space(u32 msg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81109d20)
Location: kernel/printk/printk.c:544
Inline: False
```
**Symbols:**

```
ffffffff81109d20-ffffffff81109e1c: log_make_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int log_make_free_space(u32 msg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fac00)
Location: kernel/printk/printk.c:544
Inline: False
```
**Symbols:**

```
ffffffff810fac00-ffffffff810facfc: log_make_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int log_make_free_space(u32 msg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81107c10)
Location: kernel/printk/printk.c:544
Inline: False
```
**Symbols:**

```
ffffffff81107c10-ffffffff81107d0c: log_make_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int log_make_free_space(u32 msg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81112fb0)
Location: kernel/printk/printk.c:544
Inline: False
```
**Symbols:**

```
ffffffff81112fb0-ffffffff811130ac: log_make_free_space (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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

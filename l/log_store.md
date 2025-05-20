# Function: <code>log_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int log_store(int facility, int level, enum log_flags flags, u64 ts_nsec, const char *dict, u16 dict_len, const char *text, u16 text_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810d6d10)
Location: kernel/printk/printk.c:423
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff810d6d10-ffffffff810d6f87: log_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int log_store(int facility, int level, enum log_flags flags, u64 ts_nsec, const char *dict, u16 dict_len, const char *text, u16 text_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810dbaa0)
Location: kernel/printk/printk.c:533
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff810dbaa0-ffffffff810dbd0d: log_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int log_store(int facility, int level, enum log_flags flags, u64 ts_nsec, const char *dict, u16 dict_len, const char *text, u16 text_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e2a60)
Location: kernel/printk/printk.c:531
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:cont_flush
```
**Symbols:**

```
ffffffff810e2a60-ffffffff810e2ccd: log_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int log_store(int facility, int level, enum log_flags flags, u64 ts_nsec, const char *dict, u16 dict_len, const char *text, u16 text_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e1ac0)
Location: kernel/printk/printk.c:580
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:cont_flush
```
**Symbols:**

```
ffffffff810e1ac0-ffffffff810e1d8d: log_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int log_store(int facility, int level, enum log_flags flags, u64 ts_nsec, const char *dict, u16 dict_len, const char *text, u16 text_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e9c20)
Location: kernel/printk/printk.c:580
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:cont_flush
```
**Symbols:**

```
ffffffff810e9c20-ffffffff810e9e86: log_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int log_store(int facility, int level, enum log_flags flags, u64 ts_nsec, const char *dict, u16 dict_len, const char *text, u16 text_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810f1ea0)
Location: kernel/printk/printk.c:584
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:cont_flush
```
**Symbols:**

```
ffffffff810f1ea0-ffffffff810f2118: log_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int log_store(int facility, int level, enum log_flags flags, u64 ts_nsec, const char *dict, u16 dict_len, const char *text, u16 text_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fd520)
Location: kernel/printk/printk.c:580
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:cont_flush
```
**Symbols:**

```
ffffffff810fd520-ffffffff810fd798: log_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff81105f90)
Location: kernel/printk/printk.c:594
Inline: True
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:cont_flush
```
**Symbols:**

```
ffffffff81105f90-ffffffff811061e9: log_store.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff81112320)
Location: kernel/printk/printk.c:604
Inline: True
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:cont_flush
```
**Symbols:**

```
ffffffff81112320-ffffffff81112579: log_store.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111db20)
Location: kernel/printk/printk.c:616
Inline: True
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:cont_flush
```
**Symbols:**

```
ffffffff8111db20-ffffffff8111dd92: log_store.constprop.0 (STB_LOCAL)
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffff800010172520)
Location: kernel/printk/printk.c:604
Inline: True
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:cont_flush
```
**Symbols:**

```
ffff800010172520-ffff8000101726fc: log_store.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (c03c523c)
Location: kernel/printk/printk.c:604
Inline: True
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:cont_flush
```
**Symbols:**

```
c03c523c-c03c5420: log_store.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (c0000000001cbcb0)
Location: kernel/printk/printk.c:604
Inline: True
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:cont_flush
```
**Symbols:**

```
c0000000001cbcb0-c0000000001cbf54: log_store.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffe00010e8e4)
Location: kernel/printk/printk.c:604
Inline: True
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:cont_flush
```
**Symbols:**

```
ffffffe00010e8e4-ffffffe00010eae0: log_store.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110a900)
Location: kernel/printk/printk.c:604
Inline: True
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:cont_flush
```
**Symbols:**

```
ffffffff8110a900-ffffffff8110ab59: log_store.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fb8b0)
Location: kernel/printk/printk.c:604
Inline: True
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:cont_flush
```
**Symbols:**

```
ffffffff810fb8b0-ffffffff810fbb09: log_store.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff811087f0)
Location: kernel/printk/printk.c:604
Inline: True
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:cont_flush
```
**Symbols:**

```
ffffffff811087f0-ffffffff81108a49: log_store.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff81113b90)
Location: kernel/printk/printk.c:604
Inline: True
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:cont_flush
```
**Symbols:**

```
ffffffff81113b90-ffffffff81113de9: log_store.constprop.0 (STB_LOCAL)
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
</ul>

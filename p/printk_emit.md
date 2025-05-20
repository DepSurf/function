# Function: <code>printk_emit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int printk_emit(int facility, int level, const char *dict, size_t dictlen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8118bd2a)
Location: kernel/printk/printk.c:1831
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_write
```
**Symbols:**

```
ffffffff8118bd2a-ffffffff8118bd88: printk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int printk_emit(int facility, int level, const char *dict, size_t dictlen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8119ea77)
Location: kernel/printk/printk.c:1918
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_write
```
**Symbols:**

```
ffffffff8119ea77-ffffffff8119ead5: printk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int printk_emit(int facility, int level, const char *dict, size_t dictlen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811ae4da)
Location: kernel/printk/printk.c:1810
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_write
```
**Symbols:**

```
ffffffff811ae4da-ffffffff811ae538: printk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int printk_emit(int facility, int level, const char *dict, size_t dictlen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e4ab7)
Location: kernel/printk/printk.c:1782
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_write
```
**Symbols:**

```
ffffffff810e4ab7-ffffffff810e4b15: printk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int printk_emit(int facility, int level, const char *dict, size_t dictlen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810ecd56)
Location: kernel/printk/printk.c:1770
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_write
```
**Symbols:**

```
ffffffff810ecd56-ffffffff810ecdb4: printk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int printk_emit(int facility, int level, const char *dict, size_t dictlen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810f4ffd)
Location: kernel/printk/printk.c:1931
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_write
```
**Symbols:**

```
ffffffff810f4ffd-ffffffff810f5058: printk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>

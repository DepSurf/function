# Function: <code>io_uring_show_fdinfo</code>

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
In <code>4.18</code>: Absent ⚠️
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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void io_uring_show_fdinfo(struct seq_file *m, struct file *f);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137fc00)
Location: fs/io_uring.c:8041
Inline: False
```
**Symbols:**

```
ffffffff8137fc00-ffffffff8137fc78: io_uring_show_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void io_uring_show_fdinfo(struct seq_file *m, struct file *f);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138e700)
Location: fs/io_uring.c:9532
Inline: False
```
**Symbols:**

```
ffffffff8138e700-ffffffff8138e797: io_uring_show_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_uring_show_fdinfo(struct seq_file *m, struct file *f);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81398020)
Location: fs/io_uring.c:9507
Inline: False
```
**Symbols:**

```
ffffffff81398020-ffffffff813980b7: io_uring_show_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_uring_show_fdinfo(struct seq_file *m, struct file *f);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e3b70)
Location: fs/io_uring.c:10183
Inline: False
```
**Symbols:**

```
ffffffff813e3b70-ffffffff813e3c07: io_uring_show_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_uring_show_fdinfo(struct seq_file *m, struct file *f);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e90355)
Location: io_uring/io_uring.c:11838
Inline: False
```
**Symbols:**

```
ffffffff81e90355-ffffffff81e9039e: io_uring_show_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_uring_show_fdinfo(struct seq_file *m, struct file *f);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/fdinfo.c (ffffffff8179b910)
Location: io_uring/fdinfo.c:209
Inline: False
```
**Symbols:**

```
ffffffff8179b910-ffffffff8179b9a9: io_uring_show_fdinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_uring_show_fdinfo(struct seq_file *m, struct file *f);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/fdinfo.c (ffffffff817dca40)
Location: io_uring/fdinfo.c:207
Inline: False
```
**Symbols:**

```
ffffffff817dca40-ffffffff817dcadc: io_uring_show_fdinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void io_uring_show_fdinfo(struct seq_file *m, struct file *f);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/fdinfo.c (0)
Location: io_uring/fdinfo.c:53
Inline: False
```
**Symbols:**

```
ffffffff821d527e-ffffffff821d529a: io_uring_show_fdinfo.cold (STB_LOCAL)
ffffffff81820650-ffffffff81820d73: io_uring_show_fdinfo (STB_GLOBAL)
```
</details>
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

# Function: <code>cec_error_inj_write</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t cec_error_inj_write(struct file *file, const char *ubuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-core.c (ffffffff81803270)
Location: drivers/media/cec/cec-core.c:203
Inline: False
```
**Symbols:**

```
ffffffff81803270-ffffffff81803356: cec_error_inj_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t cec_error_inj_write(struct file *file, const char *ubuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-core.c (ffffffff81844740)
Location: drivers/media/cec/cec-core.c:205
Inline: False
```
**Symbols:**

```
ffffffff81844740-ffffffff81844825: cec_error_inj_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t cec_error_inj_write(struct file *file, const char *ubuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-core.c (ffffffff81876070)
Location: drivers/media/cec/cec-core.c:205
Inline: False
```
**Symbols:**

```
ffffffff81876070-ffffffff81876155: cec_error_inj_write (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
ssize_t cec_error_inj_write(struct file *file, const char *ubuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-core.c (ffff800010abdb18)
Location: drivers/media/cec/cec-core.c:205
Inline: False
```
**Symbols:**

```
ffff800010abdb18-ffff800010abdc24: cec_error_inj_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t cec_error_inj_write(struct file *file, const char *ubuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-core.c (c0b9f98c)
Location: drivers/media/cec/cec-core.c:205
Inline: False
```
**Symbols:**

```
c0b9f98c-c0b9fa94: cec_error_inj_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t cec_error_inj_write(struct file *file, const char *ubuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-core.c (c000000000b9ebc0)
Location: drivers/media/cec/cec-core.c:205
Inline: False
```
**Symbols:**

```
c000000000b9ebc0-c000000000b9ed2c: cec_error_inj_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t cec_error_inj_write(struct file *file, const char *ubuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-core.c (ffffffe0006bf62c)
Location: drivers/media/cec/cec-core.c:205
Inline: False
```
**Symbols:**

```
ffffffe0006bf62c-ffffffe0006bf6ee: cec_error_inj_write (STB_LOCAL)
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
ssize_t cec_error_inj_write(struct file *file, const char *ubuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-core.c (ffffffff8181e5e0)
Location: drivers/media/cec/cec-core.c:205
Inline: False
```
**Symbols:**

```
ffffffff8181e5e0-ffffffff8181e6c5: cec_error_inj_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t cec_error_inj_write(struct file *file, const char *ubuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-core.c (ffffffff817e5c80)
Location: drivers/media/cec/cec-core.c:205
Inline: False
```
**Symbols:**

```
ffffffff817e5c80-ffffffff817e5d65: cec_error_inj_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t cec_error_inj_write(struct file *file, const char *ubuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-core.c (ffffffff8186b520)
Location: drivers/media/cec/cec-core.c:205
Inline: False
```
**Symbols:**

```
ffffffff8186b520-ffffffff8186b605: cec_error_inj_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t cec_error_inj_write(struct file *file, const char *ubuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-core.c (ffffffff818854b0)
Location: drivers/media/cec/cec-core.c:205
Inline: False
```
**Symbols:**

```
ffffffff818854b0-ffffffff81885595: cec_error_inj_write (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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

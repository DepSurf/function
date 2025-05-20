# Function: <code>lockdown_write</code>

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
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t lockdown_write(struct file *file, const char *buf, size_t n, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (0)
Location: security/lockdown/lockdown.c:144
Inline: False
```
**Symbols:**

```
ffffffff814b37a0-ffffffff814b387b: lockdown_write (STB_LOCAL)
ffffffff814b39f5-ffffffff814b3a17: lockdown_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t lockdown_write(struct file *file, const char *buf, size_t n, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (0)
Location: security/lockdown/lockdown.c:122
Inline: False
```
**Symbols:**

```
ffffffff81512cc0-ffffffff81512daa: lockdown_write (STB_LOCAL)
ffffffff81512f25-ffffffff81512f4b: lockdown_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t lockdown_write(struct file *file, const char *buf, size_t n, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (0)
Location: security/lockdown/lockdown.c:122
Inline: False
```
**Symbols:**

```
ffffffff8152fe90-ffffffff8152ff7a: lockdown_write (STB_LOCAL)
ffffffff81bf196d-ffffffff81bf1993: lockdown_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t lockdown_write(struct file *file, const char *buf, size_t n, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (0)
Location: security/lockdown/lockdown.c:122
Inline: False
```
**Symbols:**

```
ffffffff81536090-ffffffff8153617a: lockdown_write (STB_LOCAL)
ffffffff81be398b-ffffffff81be39b1: lockdown_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t lockdown_write(struct file *file, const char *buf, size_t n, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (0)
Location: security/lockdown/lockdown.c:122
Inline: False
```
**Symbols:**

```
ffffffff815946b0-ffffffff815947b0: lockdown_write (STB_LOCAL)
ffffffff81cd6ac2-ffffffff81cd6ae4: lockdown_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t lockdown_write(struct file *file, const char *buf, size_t n, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (0)
Location: security/lockdown/lockdown.c:122
Inline: False
```
**Symbols:**

```
ffffffff81636780-ffffffff81636892: lockdown_write (STB_LOCAL)
ffffffff81e89a06-ffffffff81e89a28: lockdown_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t lockdown_write(struct file *file, const char *buf, size_t n, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff816ed8b0)
Location: security/lockdown/lockdown.c:124
Inline: False
```
**Symbols:**

```
ffffffff816ed8b0-ffffffff816ed9dd: lockdown_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t lockdown_write(struct file *file, const char *buf, size_t n, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff81727cc0)
Location: security/lockdown/lockdown.c:124
Inline: False
```
**Symbols:**

```
ffffffff81727cc0-ffffffff81727ded: lockdown_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t lockdown_write(struct file *file, const char *buf, size_t n, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff81768ff0)
Location: security/lockdown/lockdown.c:123
Inline: False
```
**Symbols:**

```
ffffffff81768ff0-ffffffff8176911d: lockdown_write (STB_LOCAL)
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
ssize_t lockdown_write(struct file *file, const char *buf, size_t n, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (ffff8000105ab498)
Location: security/lockdown/lockdown.c:144
Inline: False
```
**Symbols:**

```
ffff8000105ab498-ffff8000105ab5bc: lockdown_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t lockdown_write(struct file *file, const char *buf, size_t n, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (c075b058)
Location: security/lockdown/lockdown.c:144
Inline: False
```
**Symbols:**

```
c075b058-c075b178: lockdown_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t lockdown_write(struct file *file, const char *buf, size_t n, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (c000000000729290)
Location: security/lockdown/lockdown.c:144
Inline: False
```
**Symbols:**

```
c000000000729290-c0000000007295a8: lockdown_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t lockdown_write(struct file *file, const char *buf, size_t n, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (ffffffe0003f4036)
Location: security/lockdown/lockdown.c:144
Inline: False
```
**Symbols:**

```
ffffffe0003f4036-ffffffe0003f413a: lockdown_write (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
ssize_t lockdown_write(struct file *file, const char *buf, size_t n, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (0)
Location: security/lockdown/lockdown.c:144
Inline: False
```
**Symbols:**

```
ffffffff814abd80-ffffffff814abe5b: lockdown_write (STB_LOCAL)
ffffffff814abfd5-ffffffff814abff7: lockdown_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t lockdown_write(struct file *file, const char *buf, size_t n, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (0)
Location: security/lockdown/lockdown.c:144
Inline: False
```
**Symbols:**

```
ffffffff8149c7a0-ffffffff8149c87b: lockdown_write (STB_LOCAL)
ffffffff8149c9f5-ffffffff8149ca17: lockdown_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t lockdown_write(struct file *file, const char *buf, size_t n, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (0)
Location: security/lockdown/lockdown.c:144
Inline: False
```
**Symbols:**

```
ffffffff814a7e20-ffffffff814a7efb: lockdown_write (STB_LOCAL)
ffffffff814a8075-ffffffff814a8097: lockdown_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t lockdown_write(struct file *file, const char *buf, size_t n, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (0)
Location: security/lockdown/lockdown.c:144
Inline: False
```
**Symbols:**

```
ffffffff814c07b0-ffffffff814c088b: lockdown_write (STB_LOCAL)
ffffffff814c0a05-ffffffff814c0a27: lockdown_write.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

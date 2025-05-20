# Function: <code>generic_fadvise</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff81206020)
Location: mm/fadvise.c:30
Inline: True
Inline callers:
  - mm/fadvise.c:vfs_fadvise
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff8121d3a0)
Location: mm/fadvise.c:30
Inline: True
Inline callers:
  - mm/fadvise.c:vfs_fadvise
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int generic_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff8122ad30)
Location: mm/fadvise.c:30
Inline: False
Direct callers:
  - mm/fadvise.c:vfs_fadvise
```
**Symbols:**

```
ffffffff8122ad30-ffffffff8122af9f: generic_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int generic_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff81257af0)
Location: mm/fadvise.c:32
Inline: False
Direct callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
**Symbols:**

```
ffffffff81257af0-ffffffff81257d5f: generic_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int generic_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff81262380)
Location: mm/fadvise.c:32
Inline: False
Direct callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
**Symbols:**

```
ffffffff81262380-ffffffff81262621: generic_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int generic_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff81266e10)
Location: mm/fadvise.c:32
Inline: False
Direct callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
**Symbols:**

```
ffffffff81266e10-ffffffff812670b5: generic_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int generic_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff812a3850)
Location: mm/fadvise.c:32
Inline: False
Direct callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
**Symbols:**

```
ffffffff812a3850-ffffffff812a3afc: generic_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int generic_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff812fb7a0)
Location: mm/fadvise.c:32
Inline: False
Direct callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
**Symbols:**

```
ffffffff812fb7a0-ffffffff812fba05: generic_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int generic_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff813658c0)
Location: mm/fadvise.c:32
Inline: False
Direct callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
**Symbols:**

```
ffffffff813658c0-ffffffff81365b69: generic_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int generic_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff81397d60)
Location: mm/fadvise.c:31
Inline: False
Direct callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
**Symbols:**

```
ffffffff81397d60-ffffffff8139803f: generic_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int generic_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff813c1b90)
Location: mm/fadvise.c:31
Inline: False
Direct callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
**Symbols:**

```
ffffffff813c1b90-ffffffff813c1e6f: generic_fadvise (STB_GLOBAL)
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
int generic_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffff8000102b8f88)
Location: mm/fadvise.c:30
Inline: False
Direct callers:
  - mm/fadvise.c:vfs_fadvise
```
**Symbols:**

```
ffff8000102b8f88-ffff8000102b9268: generic_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int generic_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (c04e5780)
Location: mm/fadvise.c:30
Inline: False
Direct callers:
  - mm/fadvise.c:vfs_fadvise
```
**Symbols:**

```
c04e5780-c04e5a60: generic_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int generic_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (c000000000371170)
Location: mm/fadvise.c:30
Inline: False
Direct callers:
  - mm/fadvise.c:vfs_fadvise
```
**Symbols:**

```
c000000000371170-c0000000003715a0: generic_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int generic_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffe0001dcbc2)
Location: mm/fadvise.c:30
Inline: False
Direct callers:
  - mm/fadvise.c:vfs_fadvise
```
**Symbols:**

```
ffffffe0001dcbc2-ffffffe0001dce42: generic_fadvise (STB_GLOBAL)
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
int generic_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff81223380)
Location: mm/fadvise.c:30
Inline: False
Direct callers:
  - mm/fadvise.c:vfs_fadvise
```
**Symbols:**

```
ffffffff81223380-ffffffff812235ef: generic_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int generic_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff81216530)
Location: mm/fadvise.c:30
Inline: False
Direct callers:
  - mm/fadvise.c:vfs_fadvise
```
**Symbols:**

```
ffffffff81216530-ffffffff8121679f: generic_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int generic_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff81221120)
Location: mm/fadvise.c:30
Inline: False
Direct callers:
  - mm/fadvise.c:vfs_fadvise
```
**Symbols:**

```
ffffffff81221120-ffffffff8122138f: generic_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int generic_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff812302e0)
Location: mm/fadvise.c:30
Inline: False
Direct callers:
  - mm/fadvise.c:vfs_fadvise
```
**Symbols:**

```
ffffffff812302e0-ffffffff8123054b: generic_fadvise (STB_GLOBAL)
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

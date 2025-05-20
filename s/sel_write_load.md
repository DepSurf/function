# Function: <code>sel_write_load</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t sel_write_load(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8134b5f0)
Location: security/selinux/selinuxfs.c:504
Inline: False
```
**Symbols:**

```
ffffffff8134b5f0-ffffffff8134bd1b: sel_write_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t sel_write_load(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff813810e0)
Location: security/selinux/selinuxfs.c:491
Inline: False
```
**Symbols:**

```
ffffffff813810e0-ffffffff81381828: sel_write_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t sel_write_load(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff81397b60)
Location: security/selinux/selinuxfs.c:493
Inline: False
```
**Symbols:**

```
ffffffff81397b60-ffffffff813982a8: sel_write_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t sel_write_load(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff813ade40)
Location: security/selinux/selinuxfs.c:472
Inline: False
```
**Symbols:**

```
ffffffff813ade40-ffffffff813ae692: sel_write_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t sel_write_load(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff813d3f00)
Location: security/selinux/selinuxfs.c:472
Inline: False
```
**Symbols:**

```
ffffffff813d3f00-ffffffff813d474e: sel_write_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
ssize_t sel_write_load(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:531
Inline: False
```
**Symbols:**

```
ffffffff81404980-ffffffff81404b24: sel_write_load (STB_LOCAL)
ffffffff81405ff5-ffffffff81406006: sel_write_load.cold.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
ssize_t sel_write_load(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:531
Inline: False
```
**Symbols:**

```
ffffffff814209e0-ffffffff81420b84: sel_write_load (STB_LOCAL)
ffffffff81421b79-ffffffff81421b8a: sel_write_load.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t sel_write_load(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:530
Inline: False
```
**Symbols:**

```
ffffffff8144e5d0-ffffffff8144e779: sel_write_load (STB_LOCAL)
ffffffff8144f72f-ffffffff8144f740: sel_write_load.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t sel_write_load(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:530
Inline: False
```
**Symbols:**

```
ffffffff814683f0-ffffffff814685a1: sel_write_load (STB_LOCAL)
ffffffff814695a7-ffffffff814695b8: sel_write_load.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t sel_write_load(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:536
Inline: False
```
**Symbols:**

```
ffffffff814bc240-ffffffff814bc3f0: sel_write_load (STB_LOCAL)
ffffffff814bd720-ffffffff814bd731: sel_write_load.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t sel_write_load(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:614
Inline: False
```
**Symbols:**

```
ffffffff814d9d00-ffffffff814d9ef8: sel_write_load (STB_LOCAL)
ffffffff81bf0539-ffffffff81bf054a: sel_write_load.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t sel_write_load(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:613
Inline: False
```
**Symbols:**

```
ffffffff814e11b0-ffffffff814e13d2: sel_write_load (STB_LOCAL)
ffffffff81be26c0-ffffffff81be26e2: sel_write_load.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t sel_write_load(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:613
Inline: False
```
**Symbols:**

```
ffffffff8153a130-ffffffff8153a352: sel_write_load (STB_LOCAL)
ffffffff81cd4129-ffffffff81cd414b: sel_write_load.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t sel_write_load(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:615
Inline: False
```
**Symbols:**

```
ffffffff815d1ae0-ffffffff815d1d1e: sel_write_load (STB_LOCAL)
ffffffff81e870ef-ffffffff81e87111: sel_write_load.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t sel_write_load(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8167f910)
Location: security/selinux/selinuxfs.c:615
Inline: False
```
**Symbols:**

```
ffffffff8167f910-ffffffff8167fb61: sel_write_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t sel_write_load(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff816b7a10)
Location: security/selinux/selinuxfs.c:580
Inline: False
```
**Symbols:**

```
ffffffff816b7a10-ffffffff816b7c4f: sel_write_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t sel_write_load(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff816f32f0)
Location: security/selinux/selinuxfs.c:570
Inline: False
```
**Symbols:**

```
ffffffff816f32f0-ffffffff816f3532: sel_write_load (STB_LOCAL)
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
ssize_t sel_write_load(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffff800010556a08)
Location: security/selinux/selinuxfs.c:530
Inline: False
```
**Symbols:**

```
ffff800010556a08-ffff800010556cf0: sel_write_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t sel_write_load(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (c070b880)
Location: security/selinux/selinuxfs.c:530
Inline: False
```
**Symbols:**

```
c070b880-c070bab4: sel_write_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t sel_write_load(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (c0000000006b3f80)
Location: security/selinux/selinuxfs.c:530
Inline: False
```
**Symbols:**

```
c0000000006b3f80-c0000000006b41ac: sel_write_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t sel_write_load(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffe0003ae690)
Location: security/selinux/selinuxfs.c:530
Inline: False
```
**Symbols:**

```
ffffffe0003ae690-ffffffe0003ae800: sel_write_load (STB_LOCAL)
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
ssize_t sel_write_load(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:530
Inline: False
```
**Symbols:**

```
ffffffff814609d0-ffffffff81460b81: sel_write_load (STB_LOCAL)
ffffffff81461b87-ffffffff81461b98: sel_write_load.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t sel_write_load(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:530
Inline: False
```
**Symbols:**

```
ffffffff81451400-ffffffff814515b1: sel_write_load (STB_LOCAL)
ffffffff814525b7-ffffffff814525c8: sel_write_load.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t sel_write_load(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:530
Inline: False
```
**Symbols:**

```
ffffffff8145ca70-ffffffff8145cc21: sel_write_load (STB_LOCAL)
ffffffff8145dc27-ffffffff8145dc38: sel_write_load.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t sel_write_load(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:530
Inline: False
```
**Symbols:**

```
ffffffff81474210-ffffffff814743c1: sel_write_load (STB_LOCAL)
ffffffff814753c7-ffffffff814753d8: sel_write_load.cold (STB_LOCAL)
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

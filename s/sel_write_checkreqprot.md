# Function: <code>sel_write_checkreqprot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t sel_write_checkreqprot(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8134a290)
Location: security/selinux/selinuxfs.c:611
Inline: False
```
**Symbols:**

```
ffffffff8134a290-ffffffff8134a392: sel_write_checkreqprot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t sel_write_checkreqprot(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff813819a0)
Location: security/selinux/selinuxfs.c:598
Inline: True
```
**Symbols:**

```
ffffffff813819a0-ffffffff81381a7a: sel_write_checkreqprot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
ssize_t sel_write_checkreqprot(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff81398420)
Location: security/selinux/selinuxfs.c:600
Inline: True
```
**Symbols:**

```
ffffffff81398420-ffffffff813984fa: sel_write_checkreqprot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t sel_write_checkreqprot(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff813ae880)
Location: security/selinux/selinuxfs.c:589
Inline: True
```
**Symbols:**

```
ffffffff813ae880-ffffffff813ae97f: sel_write_checkreqprot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t sel_write_checkreqprot(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff813d4930)
Location: security/selinux/selinuxfs.c:589
Inline: True
```
**Symbols:**

```
ffffffff813d4930-ffffffff813d4a2f: sel_write_checkreqprot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t sel_write_checkreqprot(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff81403080)
Location: security/selinux/selinuxfs.c:640
Inline: False
```
**Symbols:**

```
ffffffff81403080-ffffffff814031a3: sel_write_checkreqprot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t sel_write_checkreqprot(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8141eb90)
Location: security/selinux/selinuxfs.c:640
Inline: False
```
**Symbols:**

```
ffffffff8141eb90-ffffffff8141ecb3: sel_write_checkreqprot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t sel_write_checkreqprot(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8144c800)
Location: security/selinux/selinuxfs.c:639
Inline: False
```
**Symbols:**

```
ffffffff8144c800-ffffffff8144c919: sel_write_checkreqprot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t sel_write_checkreqprot(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff814665f0)
Location: security/selinux/selinuxfs.c:639
Inline: False
```
**Symbols:**

```
ffffffff814665f0-ffffffff81466711: sel_write_checkreqprot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t sel_write_checkreqprot(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:641
Inline: False
```
**Symbols:**

```
ffffffff814bae30-ffffffff814baf8e: sel_write_checkreqprot (STB_LOCAL)
ffffffff814bd695-ffffffff814bd6bd: sel_write_checkreqprot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t sel_write_checkreqprot(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:724
Inline: False
```
**Symbols:**

```
ffffffff814d8570-ffffffff814d86d0: sel_write_checkreqprot (STB_LOCAL)
ffffffff81bf04b8-ffffffff81bf04e0: sel_write_checkreqprot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t sel_write_checkreqprot(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:724
Inline: False
```
**Symbols:**

```
ffffffff814deed0-ffffffff814df035: sel_write_checkreqprot (STB_LOCAL)
ffffffff81be2619-ffffffff81be2641: sel_write_checkreqprot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t sel_write_checkreqprot(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:724
Inline: False
```
**Symbols:**

```
ffffffff815386c0-ffffffff81538845: sel_write_checkreqprot (STB_LOCAL)
ffffffff81cd4079-ffffffff81cd40ba: sel_write_checkreqprot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t sel_write_checkreqprot(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:726
Inline: False
```
**Symbols:**

```
ffffffff815cf230-ffffffff815cf39e: sel_write_checkreqprot (STB_LOCAL)
ffffffff81e86fb1-ffffffff81e87008: sel_write_checkreqprot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t sel_write_checkreqprot(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8167cde0)
Location: security/selinux/selinuxfs.c:726
Inline: False
```
**Symbols:**

```
ffffffff8167cde0-ffffffff8167cfaa: sel_write_checkreqprot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t sel_write_checkreqprot(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff816b4ff0)
Location: security/selinux/selinuxfs.c:686
Inline: False
```
**Symbols:**

```
ffffffff816b4ff0-ffffffff816b514d: sel_write_checkreqprot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t sel_write_checkreqprot(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff816f1b50)
Location: security/selinux/selinuxfs.c:676
Inline: False
```
**Symbols:**

```
ffffffff816f1b50-ffffffff816f1cb0: sel_write_checkreqprot (STB_LOCAL)
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
ssize_t sel_write_checkreqprot(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffff8000105548d8)
Location: security/selinux/selinuxfs.c:639
Inline: False
```
**Symbols:**

```
ffff8000105548d8-ffff800010554a14: sel_write_checkreqprot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t sel_write_checkreqprot(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (c0709a3c)
Location: security/selinux/selinuxfs.c:639
Inline: False
```
**Symbols:**

```
c0709a3c-c0709b80: sel_write_checkreqprot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t sel_write_checkreqprot(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (c0000000006b1950)
Location: security/selinux/selinuxfs.c:639
Inline: False
```
**Symbols:**

```
c0000000006b1950-c0000000006b1ac8: sel_write_checkreqprot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t sel_write_checkreqprot(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffe0003ace30)
Location: security/selinux/selinuxfs.c:639
Inline: False
```
**Symbols:**

```
ffffffe0003ace30-ffffffe0003acf06: sel_write_checkreqprot (STB_LOCAL)
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
ssize_t sel_write_checkreqprot(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8145ebd0)
Location: security/selinux/selinuxfs.c:639
Inline: False
```
**Symbols:**

```
ffffffff8145ebd0-ffffffff8145ecf1: sel_write_checkreqprot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t sel_write_checkreqprot(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8144f600)
Location: security/selinux/selinuxfs.c:639
Inline: False
```
**Symbols:**

```
ffffffff8144f600-ffffffff8144f721: sel_write_checkreqprot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t sel_write_checkreqprot(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8145ac70)
Location: security/selinux/selinuxfs.c:639
Inline: False
```
**Symbols:**

```
ffffffff8145ac70-ffffffff8145ad91: sel_write_checkreqprot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t sel_write_checkreqprot(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff81472410)
Location: security/selinux/selinuxfs.c:639
Inline: False
```
**Symbols:**

```
ffffffff81472410-ffffffff81472531: sel_write_checkreqprot (STB_LOCAL)
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

# Function: <code>smk_read_direct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_direct(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff81364750)
Location: security/smack/smackfs.c:1664
Inline: True
```
**Symbols:**

```
ffffffff81364750-ffffffff81364811: smk_read_direct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_direct(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff8139a790)
Location: security/smack/smackfs.c:1638
Inline: True
```
**Symbols:**

```
ffffffff8139a790-ffffffff8139a851: smk_read_direct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_direct(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff813b1480)
Location: security/smack/smackfs.c:1638
Inline: True
```
**Symbols:**

```
ffffffff813b1480-ffffffff813b1541: smk_read_direct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_direct(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff813c7d80)
Location: security/smack/smackfs.c:1643
Inline: True
```
**Symbols:**

```
ffffffff813c7d80-ffffffff813c7e2a: smk_read_direct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_direct(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff813ee210)
Location: security/smack/smackfs.c:1643
Inline: True
```
**Symbols:**

```
ffffffff813ee210-ffffffff813ee2ba: smk_read_direct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t smk_read_direct(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smackfs.c (0)
Location: security/smack/smackfs.c:1643
Inline: True
```
**Symbols:**

```
ffffffff8141f2e0-ffffffff8141f37a: smk_read_direct (STB_LOCAL)
ffffffff81420a04-ffffffff81420a1c: smk_read_direct.cold.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t smk_read_direct(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smackfs.c (ffffffff8143bcab)
Location: security/smack/smackfs.c:1643
Inline: True
```
**Symbols:**

```
ffffffff8143bc50-ffffffff8143bcea: smk_read_direct (STB_LOCAL)
ffffffff8143d054-ffffffff8143d06c: smk_read_direct.cold.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t smk_read_direct(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smackfs.c (ffffffff8146988d)
Location: security/smack/smackfs.c:1615
Inline: True
```
**Symbols:**

```
ffffffff81469830-ffffffff814698cc: smk_read_direct (STB_LOCAL)
ffffffff8146abf1-ffffffff8146ac09: smk_read_direct.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t smk_read_direct(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smackfs.c (ffffffff8148366d)
Location: security/smack/smackfs.c:1615
Inline: True
```
**Symbols:**

```
ffffffff81483610-ffffffff814836ac: smk_read_direct (STB_LOCAL)
ffffffff814849d1-ffffffff814849e9: smk_read_direct.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t smk_read_direct(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smackfs.c (ffffffff814d94ad)
Location: security/smack/smackfs.c:1634
Inline: True
```
**Symbols:**

```
ffffffff814d9450-ffffffff814d94ec: smk_read_direct (STB_LOCAL)
ffffffff814dab21-ffffffff814dab39: smk_read_direct.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t smk_read_direct(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smackfs.c (ffffffff814f6a3d)
Location: security/smack/smackfs.c:1638
Inline: True
```
**Symbols:**

```
ffffffff814f69e0-ffffffff814f6a7c: smk_read_direct (STB_LOCAL)
ffffffff81bf1344-ffffffff81bf135c: smk_read_direct.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t smk_read_direct(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smackfs.c (ffffffff814fd67d)
Location: security/smack/smackfs.c:1640
Inline: True
```
**Symbols:**

```
ffffffff814fd620-ffffffff814fd6bc: smk_read_direct (STB_LOCAL)
ffffffff81be34cd-ffffffff81be34e5: smk_read_direct.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t smk_read_direct(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smackfs.c (ffffffff815583cd)
Location: security/smack/smackfs.c:1641
Inline: True
```
**Symbols:**

```
ffffffff81558370-ffffffff8155840c: smk_read_direct (STB_LOCAL)
ffffffff81cd55fb-ffffffff81cd5613: smk_read_direct.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t smk_read_direct(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smackfs.c (0)
Location: security/smack/smackfs.c:1640
Inline: False
```
**Symbols:**

```
ffffffff815f1cc0-ffffffff815f1d79: smk_read_direct (STB_LOCAL)
ffffffff81e8835d-ffffffff81e88375: smk_read_direct.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t smk_read_direct(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff816a2440)
Location: security/smack/smackfs.c:1640
Inline: False
```
**Symbols:**

```
ffffffff816a2440-ffffffff816a2509: smk_read_direct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t smk_read_direct(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff816db250)
Location: security/smack/smackfs.c:1651
Inline: False
```
**Symbols:**

```
ffffffff816db250-ffffffff816db319: smk_read_direct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t smk_read_direct(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff817179d0)
Location: security/smack/smackfs.c:1659
Inline: False
```
**Symbols:**

```
ffffffff817179d0-ffffffff81717a99: smk_read_direct (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_direct(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffff800010575288)
Location: security/smack/smackfs.c:1615
Inline: True
```
**Symbols:**

```
ffff800010575288-ffff80001057535c: smk_read_direct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_direct(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (c072839c)
Location: security/smack/smackfs.c:1615
Inline: True
```
**Symbols:**

```
c072839c-c0728470: smk_read_direct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_direct(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (c0000000006de2e0)
Location: security/smack/smackfs.c:1615
Inline: True
```
**Symbols:**

```
c0000000006de2e0-c0000000006de3fc: smk_read_direct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_direct(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffe0003c83e2)
Location: security/smack/smackfs.c:1615
Inline: True
```
**Symbols:**

```
ffffffe0003c83e2-ffffffe0003c8450: smk_read_direct (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t smk_read_direct(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smackfs.c (ffffffff8147bc4d)
Location: security/smack/smackfs.c:1615
Inline: True
```
**Symbols:**

```
ffffffff8147bbf0-ffffffff8147bc8c: smk_read_direct (STB_LOCAL)
ffffffff8147cfb1-ffffffff8147cfc9: smk_read_direct.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t smk_read_direct(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smackfs.c (ffffffff8146c66d)
Location: security/smack/smackfs.c:1615
Inline: True
```
**Symbols:**

```
ffffffff8146c610-ffffffff8146c6ac: smk_read_direct (STB_LOCAL)
ffffffff8146d9d1-ffffffff8146d9e9: smk_read_direct.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t smk_read_direct(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smackfs.c (ffffffff81477ced)
Location: security/smack/smackfs.c:1615
Inline: True
```
**Symbols:**

```
ffffffff81477c90-ffffffff81477d2c: smk_read_direct (STB_LOCAL)
ffffffff81479051-ffffffff81479069: smk_read_direct.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t smk_read_direct(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smackfs.c (ffffffff8148f79d)
Location: security/smack/smackfs.c:1615
Inline: True
```
**Symbols:**

```
ffffffff8148f740-ffffffff8148f7dc: smk_read_direct (STB_LOCAL)
ffffffff81490b01-ffffffff81490b19: smk_read_direct.cold (STB_LOCAL)
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

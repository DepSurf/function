# Function: <code>smk_fetch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81361010)
Location: security/smack/smack_lsm.c:261
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff81361010-ffffffff813610ab: smk_fetch.isra.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct smack_known *smk_fetch(const char *name, struct inode *ip, struct dentry *dp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81394400)
Location: security/smack/smack_lsm.c:261
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff81394400-ffffffff813944a5: smk_fetch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813adda0)
Location: security/smack/smack_lsm.c:261
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
Direct callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff813adbb0-ffffffff813adc3b: smk_fetch.part.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813c2d41)
Location: security/smack/smack_lsm.c:262
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
Direct callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff813c2b60-ffffffff813c2beb: smk_fetch.part.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813e9001)
Location: security/smack/smack_lsm.c:262
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
Direct callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff813e8e20-ffffffff813e8eab: smk_fetch.part.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81419ecd)
Location: security/smack/smack_lsm.c:262
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
Direct callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff81419cf0-ffffffff81419d7b: smk_fetch.part.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8143669b)
Location: security/smack/smack_lsm.c:280
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
Direct callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff814364b0-ffffffff8143653b: smk_fetch.part.28 (STB_LOCAL)
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
In security/smack/smack_lsm.c (ffffffff81464375)
Location: security/smack/smack_lsm.c:281
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
Direct callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff814641a0-ffffffff8146422b: smk_fetch.part.0 (STB_LOCAL)
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
In security/smack/smack_lsm.c (ffffffff8147e145)
Location: security/smack/smack_lsm.c:281
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
Direct callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff8147df70-ffffffff8147dffb: smk_fetch.part.0 (STB_LOCAL)
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
In security/smack/smack_lsm.c (ffffffff814d3bc6)
Location: security/smack/smack_lsm.c:278
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
Direct callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff814d3970-ffffffff814d39fa: smk_fetch.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814f0d86)
Location: security/smack/smack_lsm.c:278
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
Direct callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff814f0b30-ffffffff814f0bba: smk_fetch.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct smack_known *smk_fetch(const char *name, struct inode *ip, struct dentry *dp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814f7a50)
Location: security/smack/smack_lsm.c:278
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff814f7a50-ffffffff814f7af4: smk_fetch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct smack_known *smk_fetch(const char *name, struct inode *ip, struct dentry *dp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81552610)
Location: security/smack/smack_lsm.c:278
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff81552610-ffffffff815526b4: smk_fetch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct smack_known *smk_fetch(const char *name, struct inode *ip, struct dentry *dp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff815ec070)
Location: security/smack/smack_lsm.c:281
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff815ec070-ffffffff815ec138: smk_fetch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct smack_known *smk_fetch(const char *name, struct inode *ip, struct dentry *dp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8169bd20)
Location: security/smack/smack_lsm.c:282
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff8169bd20-ffffffff8169bde8: smk_fetch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct smack_known *smk_fetch(const char *name, struct inode *ip, struct dentry *dp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff816d48a0)
Location: security/smack/smack_lsm.c:282
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff816d48a0-ffffffff816d4968: smk_fetch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct smack_known *smk_fetch(const char *name, struct inode *ip, struct dentry *dp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81710bc0)
Location: security/smack/smack_lsm.c:292
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff81710bc0-ffffffff81710cb7: smk_fetch (STB_LOCAL)
```
</details>
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
In security/smack/smack_lsm.c (ffff80001056efa0)
Location: security/smack/smack_lsm.c:281
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
Direct callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffff80001056eda0-ffff80001056ee44: smk_fetch.part.0 (STB_LOCAL)
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
In security/smack/smack_lsm.c (c0722994)
Location: security/smack/smack_lsm.c:281
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
Direct callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
c0722788-c0722828: smk_fetch.part.0 (STB_LOCAL)
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
In security/smack/smack_lsm.c (c0000000006d5a38)
Location: security/smack/smack_lsm.c:281
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
Direct callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
c0000000006d5750-c0000000006d5864: smk_fetch.part.0 (STB_LOCAL)
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
In security/smack/smack_lsm.c (ffffffe0003c4eb6)
Location: security/smack/smack_lsm.c:281
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
Direct callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffe0003c4d1c-ffffffe0003c4dae: smk_fetch.part.0 (STB_LOCAL)
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
In security/smack/smack_lsm.c (ffffffff81476725)
Location: security/smack/smack_lsm.c:281
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
Direct callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff81476550-ffffffff814765db: smk_fetch.part.0 (STB_LOCAL)
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
In security/smack/smack_lsm.c (ffffffff81467145)
Location: security/smack/smack_lsm.c:281
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
Direct callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff81466f70-ffffffff81466ffb: smk_fetch.part.0 (STB_LOCAL)
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
In security/smack/smack_lsm.c (ffffffff814727c5)
Location: security/smack/smack_lsm.c:281
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
Direct callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff814725f0-ffffffff8147267b: smk_fetch.part.0 (STB_LOCAL)
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
In security/smack/smack_lsm.c (ffffffff8148a0b5)
Location: security/smack/smack_lsm.c:281
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
Direct callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff81489ee0-ffffffff81489f6b: smk_fetch.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

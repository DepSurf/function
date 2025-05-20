# Function: <code>genfs_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8135407e)
Location: security/selinux/ss/policydb.c:1996
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81389716)
Location: security/selinux/ss/policydb.c:1996
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813a0c8b)
Location: security/selinux/ss/policydb.c:1999
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813b6cf0)
Location: security/selinux/ss/policydb.c:1992
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813dce52)
Location: security/selinux/ss/policydb.c:1992
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8140e2f9)
Location: security/selinux/ss/policydb.c:1992
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8142a1dc)
Location: security/selinux/ss/policydb.c:2002
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int genfs_read(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:1953
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81457020-ffffffff814573ae: genfs_read (STB_LOCAL)
ffffffff81458964-ffffffff8145899d: genfs_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int genfs_read(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:1955
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81470dc0-ffffffff8147114e: genfs_read (STB_LOCAL)
ffffffff81472704-ffffffff8147273d: genfs_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int genfs_read(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:2073
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff814c6250-ffffffff814c65de: genfs_read (STB_LOCAL)
ffffffff814c7949-ffffffff814c7982: genfs_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int genfs_read(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:2105
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff814e4290-ffffffff814e461e: genfs_read (STB_LOCAL)
ffffffff81bf0b54-ffffffff81bf0b8d: genfs_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int genfs_read(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:2103
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff814eac50-ffffffff814eafde: genfs_read (STB_LOCAL)
ffffffff81be2cb3-ffffffff81be2cec: genfs_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int genfs_read(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:2103
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81544690-ffffffff81544a1e: genfs_read (STB_LOCAL)
ffffffff81cd47f0-ffffffff81cd4829: genfs_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int genfs_read(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:2097
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff815dd000-ffffffff815dd3d5: genfs_read (STB_LOCAL)
ffffffff81e876d1-ffffffff81e8771f: genfs_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int genfs_read(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8168bc90)
Location: security/selinux/ss/policydb.c:2097
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff8168bc90-ffffffff8168c0b0: genfs_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int genfs_read(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816c4010)
Location: security/selinux/ss/policydb.c:2097
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff816c4010-ffffffff816c441e: genfs_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int genfs_read(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81700b10)
Location: security/selinux/ss/policydb.c:2121
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81700b10-ffffffff81700f6d: genfs_read (STB_LOCAL)
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
int genfs_read(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffff8000105605a8)
Location: security/selinux/ss/policydb.c:1955
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffff8000105605a8-ffff800010560904: genfs_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int genfs_read(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c0714e18)
Location: security/selinux/ss/policydb.c:1955
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
c0714e18-c071518c: genfs_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int genfs_read(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c0000000006c1360)
Location: security/selinux/ss/policydb.c:1955
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
c0000000006c1360-c0000000006c1a10: genfs_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffe0003b7c5e)
Location: security/selinux/ss/policydb.c:1955
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
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
int genfs_read(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:1955
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff814693a0-ffffffff8146972e: genfs_read (STB_LOCAL)
ffffffff8146ace4-ffffffff8146ad1d: genfs_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int genfs_read(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:1955
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81459dd0-ffffffff8145a15e: genfs_read (STB_LOCAL)
ffffffff8145b714-ffffffff8145b74d: genfs_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int genfs_read(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:1955
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81465440-ffffffff814657ce: genfs_read (STB_LOCAL)
ffffffff81466d84-ffffffff81466dbd: genfs_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int genfs_read(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:1955
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff8147cc20-ffffffff8147cfae: genfs_read (STB_LOCAL)
ffffffff8147e564-ffffffff8147e59d: genfs_read.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

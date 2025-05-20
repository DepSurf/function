# Function: <code>range_read</code>

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
In security/selinux/ss/policydb.c (ffffffff813541b9)
Location: security/selinux/ss/policydb.c:1841
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
In security/selinux/ss/policydb.c (ffffffff8138a1a3)
Location: security/selinux/ss/policydb.c:1841
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
In security/selinux/ss/policydb.c (ffffffff813a0dcd)
Location: security/selinux/ss/policydb.c:1844
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
In security/selinux/ss/policydb.c (ffffffff813b71d3)
Location: security/selinux/ss/policydb.c:1838
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
In security/selinux/ss/policydb.c (ffffffff813dd33b)
Location: security/selinux/ss/policydb.c:1838
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
In security/selinux/ss/policydb.c (ffffffff8140e3b9)
Location: security/selinux/ss/policydb.c:1838
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
In security/selinux/ss/policydb.c (ffffffff8142a564)
Location: security/selinux/ss/policydb.c:1848
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
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
In security/selinux/ss/policydb.c (ffffffff81457edb)
Location: security/selinux/ss/policydb.c:1799
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81471c7b)
Location: security/selinux/ss/policydb.c:1801
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int range_read(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:1782
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff814c5110-ffffffff814c535c: range_read (STB_LOCAL)
ffffffff814c7876-ffffffff814c789d: range_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int range_read(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:1814
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff814e2ef0-ffffffff814e31c7: range_read (STB_LOCAL)
ffffffff81bf0a85-ffffffff81bf0aa8: range_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int range_read(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:1812
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff814e9750-ffffffff814e99fa: range_read (STB_LOCAL)
ffffffff81be2bd6-ffffffff81be2bf9: range_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int range_read(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:1812
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff815430c0-ffffffff8154336a: range_read (STB_LOCAL)
ffffffff81cd4713-ffffffff81cd4736: range_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int range_read(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:1806
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff815da690-ffffffff815da956: range_read (STB_LOCAL)
ffffffff81e87619-ffffffff81e8762f: range_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int range_read(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81688dd0)
Location: security/selinux/ss/policydb.c:1806
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81688dd0-ffffffff816890ac: range_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int range_read(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816c2480)
Location: security/selinux/ss/policydb.c:1806
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff816c2480-ffffffff816c275d: range_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int range_read(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816fefa0)
Location: security/selinux/ss/policydb.c:1830
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff816fefa0-ffffffff816ff2db: range_read (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffff8000105613d4)
Location: security/selinux/ss/policydb.c:1801
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c0715bcc)
Location: security/selinux/ss/policydb.c:1801
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c0000000006c27c8)
Location: security/selinux/ss/policydb.c:1801
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
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
In security/selinux/ss/policydb.c (ffffffe0003b7f4c)
Location: security/selinux/ss/policydb.c:1801
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8146a25b)
Location: security/selinux/ss/policydb.c:1801
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8145ac8b)
Location: security/selinux/ss/policydb.c:1801
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814662fb)
Location: security/selinux/ss/policydb.c:1801
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8147dadb)
Location: security/selinux/ss/policydb.c:1801
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
```
</details>
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

# Function: <code>avtab_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int avtab_read(struct avtab *a, void *fp, struct policydb *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff8134ff80)
Location: security/selinux/ss/avtab.c:556
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff8134ff80-ffffffff8135007d: avtab_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int avtab_read(struct avtab *a, void *fp, struct policydb *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff81385fc0)
Location: security/selinux/ss/avtab.c:556
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81385fc0-ffffffff813860bf: avtab_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int avtab_read(struct avtab *a, void *fp, struct policydb *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff8139ca50)
Location: security/selinux/ss/avtab.c:556
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff8139ca50-ffffffff8139cb4f: avtab_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int avtab_read(struct avtab *a, void *fp, struct policydb *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff813b3190)
Location: security/selinux/ss/avtab.c:556
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff813b3190-ffffffff813b3298: avtab_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int avtab_read(struct avtab *a, void *fp, struct policydb *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff813d92e0)
Location: security/selinux/ss/avtab.c:556
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff813d92e0-ffffffff813d93e8: avtab_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int avtab_read(struct avtab *a, void *fp, struct policydb *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (0)
Location: security/selinux/ss/avtab.c:556
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81409b7a-ffffffff81409bbe: avtab_read.cold.7 (STB_LOCAL)
ffffffff814097e0-ffffffff814098b5: avtab_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int avtab_read(struct avtab *a, void *fp, struct policydb *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (0)
Location: security/selinux/ss/avtab.c:557
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81425e5d-ffffffff81425ea1: avtab_read.cold.5 (STB_LOCAL)
ffffffff81425b20-ffffffff81425bf5: avtab_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int avtab_read(struct avtab *a, void *fp, struct policydb *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (0)
Location: security/selinux/ss/avtab.c:555
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81453897-ffffffff814538e7: avtab_read.cold (STB_LOCAL)
ffffffff81453550-ffffffff8145360a: avtab_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int avtab_read(struct avtab *a, void *fp, struct policydb *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (0)
Location: security/selinux/ss/avtab.c:555
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff8146d637-ffffffff8146d687: avtab_read.cold (STB_LOCAL)
ffffffff8146d2f0-ffffffff8146d3aa: avtab_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int avtab_read(struct avtab *a, void *fp, struct policydb *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (0)
Location: security/selinux/ss/avtab.c:554
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff814c1e23-ffffffff814c1e73: avtab_read.cold (STB_LOCAL)
ffffffff814c1ae0-ffffffff814c1b9a: avtab_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int avtab_read(struct avtab *a, void *fp, struct policydb *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (0)
Location: security/selinux/ss/avtab.c:601
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81bf085a-ffffffff81bf08aa: avtab_read.cold (STB_LOCAL)
ffffffff814df710-ffffffff814df7ca: avtab_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int avtab_read(struct avtab *a, void *fp, struct policydb *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (0)
Location: security/selinux/ss/avtab.c:566
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81be29a7-ffffffff81be29f7: avtab_read.cold (STB_LOCAL)
ffffffff814e6010-ffffffff814e60ca: avtab_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int avtab_read(struct avtab *a, void *fp, struct policydb *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (0)
Location: security/selinux/ss/avtab.c:568
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81cd44e4-ffffffff81cd4534: avtab_read.cold (STB_LOCAL)
ffffffff8153f870-ffffffff8153f92a: avtab_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int avtab_read(struct avtab *a, void *fp, struct policydb *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (0)
Location: security/selinux/ss/avtab.c:568
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81e87416-ffffffff81e8745c: avtab_read.cold (STB_LOCAL)
ffffffff815d75c0-ffffffff815d7686: avtab_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int avtab_read(struct avtab *a, void *fp, struct policydb *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff81685b20)
Location: security/selinux/ss/avtab.c:568
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81685b20-ffffffff81685c17: avtab_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int avtab_read(struct avtab *a, void *fp, struct policydb *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff816bde80)
Location: security/selinux/ss/avtab.c:568
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff816bde80-ffffffff816bdf77: avtab_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int avtab_read(struct avtab *a, void *fp, struct policydb *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff816fa730)
Location: security/selinux/ss/avtab.c:504
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff816fa730-ffffffff816fa827: avtab_read (STB_GLOBAL)
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
int avtab_read(struct avtab *a, void *fp, struct policydb *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffff80001055c458)
Location: security/selinux/ss/avtab.c:555
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffff80001055c458-ffff80001055c598: avtab_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int avtab_read(struct avtab *a, void *fp, struct policydb *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (c0710bf4)
Location: security/selinux/ss/avtab.c:555
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
c0710bf4-c0710d1c: avtab_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int avtab_read(struct avtab *a, void *fp, struct policydb *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (c0000000006bbb50)
Location: security/selinux/ss/avtab.c:555
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
c0000000006bbb50-c0000000006bbd00: avtab_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int avtab_read(struct avtab *a, void *fp, struct policydb *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffe0003b314a)
Location: security/selinux/ss/avtab.c:555
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffe0003b314a-ffffffe0003b3268: avtab_read (STB_GLOBAL)
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
int avtab_read(struct avtab *a, void *fp, struct policydb *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (0)
Location: security/selinux/ss/avtab.c:555
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81465c17-ffffffff81465c67: avtab_read.cold (STB_LOCAL)
ffffffff814658d0-ffffffff8146598a: avtab_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int avtab_read(struct avtab *a, void *fp, struct policydb *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (0)
Location: security/selinux/ss/avtab.c:555
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81456647-ffffffff81456697: avtab_read.cold (STB_LOCAL)
ffffffff81456300-ffffffff814563ba: avtab_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int avtab_read(struct avtab *a, void *fp, struct policydb *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (0)
Location: security/selinux/ss/avtab.c:555
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81461cb7-ffffffff81461d07: avtab_read.cold (STB_LOCAL)
ffffffff81461970-ffffffff81461a2a: avtab_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int avtab_read(struct avtab *a, void *fp, struct policydb *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (0)
Location: security/selinux/ss/avtab.c:555
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff814794b7-ffffffff81479507: avtab_read.cold (STB_LOCAL)
ffffffff81479170-ffffffff8147922a: avtab_read (STB_GLOBAL)
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

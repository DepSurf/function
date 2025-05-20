# Function: <code>cond_read_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cond_read_list(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff8135b250)
Location: security/selinux/ss/conditional.c:453
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff8135b250-ffffffff8135b507: cond_read_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cond_read_list(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff81391200)
Location: security/selinux/ss/conditional.c:453
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81391200-ffffffff813914b8: cond_read_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cond_read_list(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff813a7e30)
Location: security/selinux/ss/conditional.c:455
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff813a7e30-ffffffff813a80e8: cond_read_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cond_read_list(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff813be7f0)
Location: security/selinux/ss/conditional.c:456
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff813be7f0-ffffffff813beaa6: cond_read_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cond_read_list(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff813e4990)
Location: security/selinux/ss/conditional.c:455
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff813e4990-ffffffff813e4c46: cond_read_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int cond_read_list(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/conditional.c (0)
Location: security/selinux/ss/conditional.c:455
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81415c33-ffffffff81415c79: cond_read_list.cold.11 (STB_LOCAL)
ffffffff81415650-ffffffff814158a4: cond_read_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int cond_read_list(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/conditional.c (0)
Location: security/selinux/ss/conditional.c:455
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff814321f3-ffffffff81432239: cond_read_list.cold.10 (STB_LOCAL)
ffffffff81431c10-ffffffff81431e6f: cond_read_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int cond_read_list(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/conditional.c (0)
Location: security/selinux/ss/conditional.c:449
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff8145fc2e-ffffffff8145fc74: cond_read_list.cold (STB_LOCAL)
ffffffff8145f680-ffffffff8145f8d0: cond_read_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int cond_read_list(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/conditional.c (0)
Location: security/selinux/ss/conditional.c:449
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff814799de-ffffffff81479a24: cond_read_list.cold (STB_LOCAL)
ffffffff81479430-ffffffff81479680: cond_read_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cond_read_list(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff814ceb30)
Location: security/selinux/ss/conditional.c:413
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff814ceb30-ffffffff814cec75: cond_read_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cond_read_list(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff814ebf70)
Location: security/selinux/ss/conditional.c:413
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff814ebf70-ffffffff814ec0b5: cond_read_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int cond_read_list(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/conditional.c (0)
Location: security/selinux/ss/conditional.c:413
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81be3310-ffffffff81be333c: cond_read_list.cold (STB_LOCAL)
ffffffff814f2980-ffffffff814f2bf8: cond_read_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cond_read_list(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/conditional.c (0)
Location: security/selinux/ss/conditional.c:416
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81cd53c9-ffffffff81cd53f5: cond_read_list.cold (STB_LOCAL)
ffffffff8154d390-ffffffff8154d583: cond_read_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cond_read_list(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/conditional.c (0)
Location: security/selinux/ss/conditional.c:416
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81e881ed-ffffffff81e8820f: cond_read_list.cold (STB_LOCAL)
ffffffff815e6380-ffffffff815e6583: cond_read_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cond_read_list(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff816959c0)
Location: security/selinux/ss/conditional.c:416
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff816959c0-ffffffff81695bdb: cond_read_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cond_read_list(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff816cded0)
Location: security/selinux/ss/conditional.c:416
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff816cded0-ffffffff816ce0eb: cond_read_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cond_read_list(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff8170a4f0)
Location: security/selinux/ss/conditional.c:416
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff8170a4f0-ffffffff8170a70b: cond_read_list (STB_GLOBAL)
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
int cond_read_list(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffff8000105698a8)
Location: security/selinux/ss/conditional.c:449
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffff8000105698a8-ffff800010569b4c: cond_read_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cond_read_list(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (c071d4d8)
Location: security/selinux/ss/conditional.c:449
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
c071d4d8-c071d78c: cond_read_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cond_read_list(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (c0000000006ccd90)
Location: security/selinux/ss/conditional.c:449
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
c0000000006ccd90-c0000000006cd0fc: cond_read_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cond_read_list(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffe0003be8d2)
Location: security/selinux/ss/conditional.c:449
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffe0003be8d2-ffffffe0003beb8a: cond_read_list (STB_GLOBAL)
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
int cond_read_list(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/conditional.c (0)
Location: security/selinux/ss/conditional.c:449
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81471fbe-ffffffff81472004: cond_read_list.cold (STB_LOCAL)
ffffffff81471a10-ffffffff81471c60: cond_read_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int cond_read_list(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/conditional.c (0)
Location: security/selinux/ss/conditional.c:449
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff814629de-ffffffff81462a24: cond_read_list.cold (STB_LOCAL)
ffffffff81462430-ffffffff81462680: cond_read_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int cond_read_list(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/conditional.c (0)
Location: security/selinux/ss/conditional.c:449
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff8146e05e-ffffffff8146e0a4: cond_read_list.cold (STB_LOCAL)
ffffffff8146dab0-ffffffff8146dd00: cond_read_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int cond_read_list(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/conditional.c (0)
Location: security/selinux/ss/conditional.c:449
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff814858ce-ffffffff81485914: cond_read_list.cold (STB_LOCAL)
ffffffff81485320-ffffffff81485570: cond_read_list (STB_GLOBAL)
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

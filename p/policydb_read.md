# Function: <code>policydb_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int policydb_read(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813531e0)
Location: security/selinux/ss/policydb.c:2234
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff813531e0-ffffffff81354763: policydb_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int policydb_read(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813891e0)
Location: security/selinux/ss/policydb.c:2234
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff813891e0-ffffffff8138a72e: policydb_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int policydb_read(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8139fca0)
Location: security/selinux/ss/policydb.c:2237
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff8139fca0-ffffffff813a1334: policydb_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int policydb_read(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813b63e0)
Location: security/selinux/ss/policydb.c:2276
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff813b63e0-ffffffff813b7a8a: policydb_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int policydb_read(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813dc540)
Location: security/selinux/ss/policydb.c:2276
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff813dc540-ffffffff813ddbf2: policydb_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int policydb_read(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:2276
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff8140e034-ffffffff8140ec23: policydb_read.cold.41 (STB_LOCAL)
ffffffff8140ca40-ffffffff8140d50b: policydb_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int policydb_read(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:2301
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff8142b029-ffffffff8142b15c: policydb_read.cold.42 (STB_LOCAL)
ffffffff81429720-ffffffff8142a8a8: policydb_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int policydb_read(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:2252
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff8145899d-ffffffff81458a9e: policydb_read.cold (STB_LOCAL)
ffffffff814573f0-ffffffff81458242: policydb_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int policydb_read(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:2254
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff8147273d-ffffffff8147283e: policydb_read.cold (STB_LOCAL)
ffffffff81471190-ffffffff81471fe2: policydb_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int policydb_read(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:2372
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff814c7982-ffffffff814c7ab0: policydb_read.cold (STB_LOCAL)
ffffffff814c6680-ffffffff814c727c: policydb_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int policydb_read(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:2404
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81bf0b8d-ffffffff81bf0cfd: policydb_read.cold (STB_LOCAL)
ffffffff814e46c0-ffffffff814e531c: policydb_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int policydb_read(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:2402
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81be2cec-ffffffff81be2e3e: policydb_read.cold (STB_LOCAL)
ffffffff814eb080-ffffffff814ebc6b: policydb_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int policydb_read(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:2402
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81cd4847-ffffffff81cd49ab: policydb_read.cold (STB_LOCAL)
ffffffff81544ad0-ffffffff815457e6: policydb_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int policydb_read(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:2396
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81e8773d-ffffffff81e87873: policydb_read.cold (STB_LOCAL)
ffffffff815dd4c0-ffffffff815de146: policydb_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int policydb_read(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8168c1c0)
Location: security/selinux/ss/policydb.c:2396
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff8168c1c0-ffffffff8168cd8a: policydb_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int policydb_read(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816c4530)
Location: security/selinux/ss/policydb.c:2400
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff816c4530-ffffffff816c50ce: policydb_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int policydb_read(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81701080)
Location: security/selinux/ss/policydb.c:2425
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81701080-ffffffff81701cd4: policydb_read (STB_GLOBAL)
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
int policydb_read(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffff8000105609b8)
Location: security/selinux/ss/policydb.c:2254
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffff8000105609b8-ffff800010561648: policydb_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int policydb_read(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c071523c)
Location: security/selinux/ss/policydb.c:2254
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
c071523c-c0715fd4: policydb_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int policydb_read(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c0000000006c1ac0)
Location: security/selinux/ss/policydb.c:2254
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
c0000000006c1ac0-c0000000006c2ae4: policydb_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int policydb_read(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffe0003b7200)
Location: security/selinux/ss/policydb.c:2254
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffe0003b7200-ffffffe0003b8350: policydb_read (STB_GLOBAL)
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
int policydb_read(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:2254
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff8146ad1d-ffffffff8146ae1e: policydb_read.cold (STB_LOCAL)
ffffffff81469770-ffffffff8146a5c2: policydb_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int policydb_read(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:2254
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff8145b74d-ffffffff8145b84e: policydb_read.cold (STB_LOCAL)
ffffffff8145a1a0-ffffffff8145aff2: policydb_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int policydb_read(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:2254
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81466dbd-ffffffff81466ebe: policydb_read.cold (STB_LOCAL)
ffffffff81465810-ffffffff81466662: policydb_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int policydb_read(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:2254
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff8147e59d-ffffffff8147e69e: policydb_read.cold (STB_LOCAL)
ffffffff8147cff0-ffffffff8147de42: policydb_read (STB_GLOBAL)
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

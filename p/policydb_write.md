# Function: <code>policydb_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int policydb_write(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81354770)
Location: security/selinux/ss/policydb.c:3334
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_read_policy
```
**Symbols:**

```
ffffffff81354770-ffffffff8135501f: policydb_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int policydb_write(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8138a730)
Location: security/selinux/ss/policydb.c:3334
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_read_policy
```
**Symbols:**

```
ffffffff8138a730-ffffffff8138af83: policydb_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int policydb_write(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813a1340)
Location: security/selinux/ss/policydb.c:3338
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_read_policy
```
**Symbols:**

```
ffffffff813a1340-ffffffff813a1b93: policydb_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int policydb_write(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813b7a90)
Location: security/selinux/ss/policydb.c:3404
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_read_policy
```
**Symbols:**

```
ffffffff813b7a90-ffffffff813b8408: policydb_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int policydb_write(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813ddc00)
Location: security/selinux/ss/policydb.c:3404
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_read_policy
```
**Symbols:**

```
ffffffff813ddc00-ffffffff813de57e: policydb_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int policydb_write(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:3404
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_read_policy
```
**Symbols:**

```
ffffffff8140ec23-ffffffff8140ec3e: policydb_write.cold.42 (STB_LOCAL)
ffffffff8140d510-ffffffff8140ddd4: policydb_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int policydb_write(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:3435
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_read_policy
```
**Symbols:**

```
ffffffff8142b15c-ffffffff8142b177: policydb_write.cold.43 (STB_LOCAL)
ffffffff8142a8b0-ffffffff8142ae5f: policydb_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int policydb_write(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:3381
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_read_policy
```
**Symbols:**

```
ffffffff81458a9e-ffffffff81458ab9: policydb_write.cold (STB_LOCAL)
ffffffff81458250-ffffffff814586af: policydb_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int policydb_write(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:3383
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_read_policy
```
**Symbols:**

```
ffffffff8147283e-ffffffff81472859: policydb_write.cold (STB_LOCAL)
ffffffff81471ff0-ffffffff8147244f: policydb_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int policydb_write(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:3570
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_read_policy
```
**Symbols:**

```
ffffffff814c7ab0-ffffffff814c7acc: policydb_write.cold (STB_LOCAL)
ffffffff814c7280-ffffffff814c76a1: policydb_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int policydb_write(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:3612
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_read_policy
```
**Symbols:**

```
ffffffff81bf0cfd-ffffffff81bf0d19: policydb_write.cold (STB_LOCAL)
ffffffff814e5320-ffffffff814e573b: policydb_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int policydb_write(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:3610
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_read_state_kernel
  - security/selinux/ss/services.c:security_read_policy
```
**Symbols:**

```
ffffffff81be2e3e-ffffffff81be2e5a: policydb_write.cold (STB_LOCAL)
ffffffff814ebc70-ffffffff814ec088: policydb_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int policydb_write(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:3609
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_read_state_kernel
  - security/selinux/ss/services.c:security_read_policy
```
**Symbols:**

```
ffffffff81cd49ab-ffffffff81cd49c7: policydb_write.cold (STB_LOCAL)
ffffffff815457f0-ffffffff81545e0e: policydb_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int policydb_write(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:3601
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_read_state_kernel
  - security/selinux/ss/services.c:security_read_policy
```
**Symbols:**

```
ffffffff81e87873-ffffffff81e8789e: policydb_write.cold (STB_LOCAL)
ffffffff815de150-ffffffff815de72f: policydb_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int policydb_write(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8168cda0)
Location: security/selinux/ss/policydb.c:3601
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_read_state_kernel
  - security/selinux/ss/services.c:security_read_policy
```
**Symbols:**

```
ffffffff8168cda0-ffffffff8168d3fc: policydb_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int policydb_write(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816c50e0)
Location: security/selinux/ss/policydb.c:3605
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_read_state_kernel
  - security/selinux/ss/services.c:security_read_policy
```
**Symbols:**

```
ffffffff816c50e0-ffffffff816c56df: policydb_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int policydb_write(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81701cf0)
Location: security/selinux/ss/policydb.c:3631
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_read_state_kernel
  - security/selinux/ss/services.c:security_read_policy
```
**Symbols:**

```
ffffffff81701cf0-ffffffff8170232a: policydb_write (STB_GLOBAL)
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
int policydb_write(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffff800010561648)
Location: security/selinux/ss/policydb.c:3383
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_read_policy
```
**Symbols:**

```
ffff800010561648-ffff800010561ad4: policydb_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int policydb_write(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c0715fd4)
Location: security/selinux/ss/policydb.c:3383
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_read_policy
```
**Symbols:**

```
c0715fd4-c0716540: policydb_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int policydb_write(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c0000000006c2af0)
Location: security/selinux/ss/policydb.c:3383
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_read_policy
```
**Symbols:**

```
c0000000006c2af0-c0000000006c30e8: policydb_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int policydb_write(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffe0003b8350)
Location: security/selinux/ss/policydb.c:3383
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_read_policy
```
**Symbols:**

```
ffffffe0003b8350-ffffffe0003b8ac2: policydb_write (STB_GLOBAL)
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
int policydb_write(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:3383
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_read_policy
```
**Symbols:**

```
ffffffff8146ae1e-ffffffff8146ae39: policydb_write.cold (STB_LOCAL)
ffffffff8146a5d0-ffffffff8146aa2f: policydb_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int policydb_write(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:3383
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_read_policy
```
**Symbols:**

```
ffffffff8145b84e-ffffffff8145b869: policydb_write.cold (STB_LOCAL)
ffffffff8145b000-ffffffff8145b45f: policydb_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int policydb_write(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:3383
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_read_policy
```
**Symbols:**

```
ffffffff81466ebe-ffffffff81466ed9: policydb_write.cold (STB_LOCAL)
ffffffff81466670-ffffffff81466acf: policydb_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int policydb_write(struct policydb *p, void *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:3383
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_read_policy
```
**Symbols:**

```
ffffffff8147e69e-ffffffff8147e6b9: policydb_write.cold (STB_LOCAL)
ffffffff8147de50-ffffffff8147e2af: policydb_write (STB_GLOBAL)
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

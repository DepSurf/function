# Function: <code>policydb_load_isids</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int policydb_load_isids(struct policydb *p, struct sidtab *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81352fe0)
Location: security/selinux/ss/policydb.c:891
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81352fe0-ffffffff81353082: policydb_load_isids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int policydb_load_isids(struct policydb *p, struct sidtab *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81388fe0)
Location: security/selinux/ss/policydb.c:891
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81388fe0-ffffffff81389082: policydb_load_isids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int policydb_load_isids(struct policydb *p, struct sidtab *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8139fa90)
Location: security/selinux/ss/policydb.c:891
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff8139fa90-ffffffff8139fb32: policydb_load_isids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int policydb_load_isids(struct policydb *p, struct sidtab *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813b61c0)
Location: security/selinux/ss/policydb.c:893
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff813b61c0-ffffffff813b6262: policydb_load_isids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int policydb_load_isids(struct policydb *p, struct sidtab *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813dc320)
Location: security/selinux/ss/policydb.c:893
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff813dc320-ffffffff813dc3c2: policydb_load_isids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int policydb_load_isids(struct policydb *p, struct sidtab *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:893
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff8140decd-ffffffff8140df0f: policydb_load_isids.cold.40 (STB_LOCAL)
ffffffff8140c850-ffffffff8140c8d3: policydb_load_isids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int policydb_load_isids(struct policydb *p, struct sidtab *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:896
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff8142af44-ffffffff8142afb8: policydb_load_isids.cold.40 (STB_LOCAL)
ffffffff81429010-ffffffff814290b1: policydb_load_isids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int policydb_load_isids(struct policydb *p, struct sidtab *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:848
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81458868-ffffffff814588dc: policydb_load_isids.cold (STB_LOCAL)
ffffffff814569c0-ffffffff81456a41: policydb_load_isids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int policydb_load_isids(struct policydb *p, struct sidtab *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:850
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81472608-ffffffff8147267c: policydb_load_isids.cold (STB_LOCAL)
ffffffff81470760-ffffffff814707e1: policydb_load_isids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int policydb_load_isids(struct policydb *p, struct sidtab *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:837
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff814c78b9-ffffffff814c7902: policydb_load_isids.cold (STB_LOCAL)
ffffffff814c5ba0-ffffffff814c5c2b: policydb_load_isids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int policydb_load_isids(struct policydb *p, struct sidtab *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:869
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81bf0ac4-ffffffff81bf0b0d: policydb_load_isids.cold (STB_LOCAL)
ffffffff814e3be0-ffffffff814e3c6b: policydb_load_isids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int policydb_load_isids(struct policydb *p, struct sidtab *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:869
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81be2c1d-ffffffff81be2c6c: policydb_load_isids.cold (STB_LOCAL)
ffffffff814ea5a0-ffffffff814ea62b: policydb_load_isids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int policydb_load_isids(struct policydb *p, struct sidtab *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:869
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81cd475a-ffffffff81cd47a9: policydb_load_isids.cold (STB_LOCAL)
ffffffff81543fc0-ffffffff8154404b: policydb_load_isids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int policydb_load_isids(struct policydb *p, struct sidtab *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:863
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81e87644-ffffffff81e87693: policydb_load_isids.cold (STB_LOCAL)
ffffffff815dc8a0-ffffffff815dc935: policydb_load_isids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int policydb_load_isids(struct policydb *p, struct sidtab *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8168b3c0)
Location: security/selinux/ss/policydb.c:863
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff8168b3c0-ffffffff8168b4bb: policydb_load_isids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int policydb_load_isids(struct policydb *p, struct sidtab *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816c3730)
Location: security/selinux/ss/policydb.c:863
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff816c3730-ffffffff816c382b: policydb_load_isids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int policydb_load_isids(struct policydb *p, struct sidtab *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff817001c0)
Location: security/selinux/ss/policydb.c:857
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff817001c0-ffffffff81700322: policydb_load_isids (STB_GLOBAL)
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
int policydb_load_isids(struct policydb *p, struct sidtab *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffff80001055fde0)
Location: security/selinux/ss/policydb.c:850
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffff80001055fde0-ffff80001055fecc: policydb_load_isids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int policydb_load_isids(struct policydb *p, struct sidtab *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c0714558)
Location: security/selinux/ss/policydb.c:850
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
c0714558-c0714644: policydb_load_isids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int policydb_load_isids(struct policydb *p, struct sidtab *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c0000000006c0900)
Location: security/selinux/ss/policydb.c:850
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
c0000000006c0900-c0000000006c0a3c: policydb_load_isids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int policydb_load_isids(struct policydb *p, struct sidtab *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffe0003b6886)
Location: security/selinux/ss/policydb.c:850
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffe0003b6886-ffffffe0003b6964: policydb_load_isids (STB_GLOBAL)
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
int policydb_load_isids(struct policydb *p, struct sidtab *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:850
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff8146abe8-ffffffff8146ac5c: policydb_load_isids.cold (STB_LOCAL)
ffffffff81468d40-ffffffff81468dc1: policydb_load_isids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int policydb_load_isids(struct policydb *p, struct sidtab *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:850
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff8145b618-ffffffff8145b68c: policydb_load_isids.cold (STB_LOCAL)
ffffffff81459770-ffffffff814597f1: policydb_load_isids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int policydb_load_isids(struct policydb *p, struct sidtab *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:850
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81466c88-ffffffff81466cfc: policydb_load_isids.cold (STB_LOCAL)
ffffffff81464de0-ffffffff81464e61: policydb_load_isids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int policydb_load_isids(struct policydb *p, struct sidtab *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:850
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff8147e468-ffffffff8147e4dc: policydb_load_isids.cold (STB_LOCAL)
ffffffff8147c5c0-ffffffff8147c641: policydb_load_isids (STB_GLOBAL)
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

# Function: <code>__aa_create_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct aa_ns *__aa_create_ns(struct aa_ns *parent, const char *name, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff813d00c0)
Location: security/apparmor/policy_ns.c:187
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:aa_create_ns
```
**Symbols:**

```
ffffffff813d00c0-ffffffff813d02e7: __aa_create_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct aa_ns *__aa_create_ns(struct aa_ns *parent, const char *name, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff813e77c0)
Location: security/apparmor/policy_ns.c:188
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:aa_create_ns
```
**Symbols:**

```
ffffffff813e77c0-ffffffff813e79ef: __aa_create_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct aa_ns *__aa_create_ns(struct aa_ns *parent, const char *name, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff813ec090)
Location: security/apparmor/policy_ns.c:246
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
```
**Symbols:**

```
ffffffff813ec090-ffffffff813ec1a2: __aa_create_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct aa_ns *__aa_create_ns(struct aa_ns *parent, const char *name, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81413a20)
Location: security/apparmor/policy_ns.c:246
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
```
**Symbols:**

```
ffffffff81413a20-ffffffff81413b3e: __aa_create_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct aa_ns *__aa_create_ns(struct aa_ns *parent, const char *name, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (0)
Location: security/apparmor/policy_ns.c:246
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
```
**Symbols:**

```
ffffffff81445e30-ffffffff81445f48: __aa_create_ns (STB_LOCAL)
ffffffff81446407-ffffffff8144641b: __aa_create_ns.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct aa_ns *__aa_create_ns(struct aa_ns *parent, const char *name, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (0)
Location: security/apparmor/policy_ns.c:246
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
```
**Symbols:**

```
ffffffff81462d50-ffffffff81462e68: __aa_create_ns (STB_LOCAL)
ffffffff81463327-ffffffff8146333b: __aa_create_ns.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct aa_ns *__aa_create_ns(struct aa_ns *parent, const char *name, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (0)
Location: security/apparmor/policy_ns.c:242
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
```
**Symbols:**

```
ffffffff8148ff70-ffffffff81490089: __aa_create_ns (STB_LOCAL)
ffffffff814905f0-ffffffff81490605: __aa_create_ns.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct aa_ns *__aa_create_ns(struct aa_ns *parent, const char *name, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (0)
Location: security/apparmor/policy_ns.c:242
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
```
**Symbols:**

```
ffffffff814a9e30-ffffffff814a9f49: __aa_create_ns (STB_LOCAL)
ffffffff814aa4b0-ffffffff814aa4c5: __aa_create_ns.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct aa_ns *__aa_create_ns(struct aa_ns *parent, const char *name, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (0)
Location: security/apparmor/policy_ns.c:242
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
```
**Symbols:**

```
ffffffff81507890-ffffffff81507a13: __aa_create_ns (STB_LOCAL)
ffffffff81508180-ffffffff81508195: __aa_create_ns.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct aa_ns *__aa_create_ns(struct aa_ns *parent, const char *name, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (0)
Location: security/apparmor/policy_ns.c:242
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
```
**Symbols:**

```
ffffffff81524930-ffffffff81524ab3: __aa_create_ns (STB_LOCAL)
ffffffff81bf17bb-ffffffff81bf17d0: __aa_create_ns.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct aa_ns *__aa_create_ns(struct aa_ns *parent, const char *name, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (0)
Location: security/apparmor/policy_ns.c:242
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
```
**Symbols:**

```
ffffffff8152aa70-ffffffff8152ac63: __aa_create_ns (STB_LOCAL)
ffffffff81be37cb-ffffffff81be37e0: __aa_create_ns.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct aa_ns *__aa_create_ns(struct aa_ns *parent, const char *name, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (0)
Location: security/apparmor/policy_ns.c:242
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
```
**Symbols:**

```
ffffffff81588e10-ffffffff81589003: __aa_create_ns (STB_LOCAL)
ffffffff81cd6709-ffffffff81cd671e: __aa_create_ns.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct aa_ns *__aa_create_ns(struct aa_ns *parent, const char *name, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (0)
Location: security/apparmor/policy_ns.c:257
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
```
**Symbols:**

```
ffffffff816296a0-ffffffff81629837: __aa_create_ns (STB_LOCAL)
ffffffff81e8963b-ffffffff81e8964f: __aa_create_ns.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct aa_ns *__aa_create_ns(struct aa_ns *parent, const char *name, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff816ddd90)
Location: security/apparmor/policy_ns.c:256
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
```
**Symbols:**

```
ffffffff816ddd90-ffffffff816ddf34: __aa_create_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct aa_ns *__aa_create_ns(struct aa_ns *parent, const char *name, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81717390)
Location: security/apparmor/policy_ns.c:256
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
```
**Symbols:**

```
ffffffff81717390-ffffffff81717534: __aa_create_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct aa_ns *__aa_create_ns(struct aa_ns *parent, const char *name, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81755f20)
Location: security/apparmor/policy_ns.c:219
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
```
**Symbols:**

```
ffffffff81755f20-ffffffff817560c4: __aa_create_ns (STB_LOCAL)
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
struct aa_ns *__aa_create_ns(struct aa_ns *parent, const char *name, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffff8000105a0868)
Location: security/apparmor/policy_ns.c:242
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
```
**Symbols:**

```
ffff8000105a0868-ffff8000105a09b0: __aa_create_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct aa_ns *__aa_create_ns(struct aa_ns *parent, const char *name, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (c075145c)
Location: security/apparmor/policy_ns.c:242
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
```
**Symbols:**

```
c075145c-c0751574: __aa_create_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct aa_ns *__aa_create_ns(struct aa_ns *parent, const char *name, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (c00000000071ad40)
Location: security/apparmor/policy_ns.c:242
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
```
**Symbols:**

```
c00000000071ad40-c00000000071af18: __aa_create_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct aa_ns *__aa_create_ns(struct aa_ns *parent, const char *name, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffe0003eb798)
Location: security/apparmor/policy_ns.c:242
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
```
**Symbols:**

```
ffffffe0003eb798-ffffffe0003eb8a2: __aa_create_ns (STB_LOCAL)
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
struct aa_ns *__aa_create_ns(struct aa_ns *parent, const char *name, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (0)
Location: security/apparmor/policy_ns.c:242
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
```
**Symbols:**

```
ffffffff814a2410-ffffffff814a2529: __aa_create_ns (STB_LOCAL)
ffffffff814a2a90-ffffffff814a2aa5: __aa_create_ns.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct aa_ns *__aa_create_ns(struct aa_ns *parent, const char *name, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (0)
Location: security/apparmor/policy_ns.c:242
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
```
**Symbols:**

```
ffffffff81492e30-ffffffff81492f49: __aa_create_ns (STB_LOCAL)
ffffffff814934b0-ffffffff814934c5: __aa_create_ns.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct aa_ns *__aa_create_ns(struct aa_ns *parent, const char *name, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (0)
Location: security/apparmor/policy_ns.c:242
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
```
**Symbols:**

```
ffffffff8149e4b0-ffffffff8149e5c9: __aa_create_ns (STB_LOCAL)
ffffffff8149eb30-ffffffff8149eb45: __aa_create_ns.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct aa_ns *__aa_create_ns(struct aa_ns *parent, const char *name, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (0)
Location: security/apparmor/policy_ns.c:242
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
```
**Symbols:**

```
ffffffff814b6aa0-ffffffff814b6bb9: __aa_create_ns (STB_LOCAL)
ffffffff814b7160-ffffffff814b7175: __aa_create_ns.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

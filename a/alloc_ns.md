# Function: <code>alloc_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct aa_ns *alloc_ns(const char *prefix, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81394670)
Location: security/apparmor/policy_ns.c:90
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
```
**Symbols:**

```
ffffffff81394670-ffffffff8139479c: alloc_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct aa_ns *alloc_ns(const char *prefix, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff813cfe50)
Location: security/apparmor/policy_ns.c:90
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff813cfe50-ffffffff813cff7c: alloc_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct aa_ns *alloc_ns(const char *prefix, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff813e7530)
Location: security/apparmor/policy_ns.c:90
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff813e7530-ffffffff813e7673: alloc_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct aa_ns *alloc_ns(const char *prefix, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff813ebe60)
Location: security/apparmor/policy_ns.c:91
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff813ebe60-ffffffff813ec019: alloc_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct aa_ns *alloc_ns(const char *prefix, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81413850)
Location: security/apparmor/policy_ns.c:91
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff81413850-ffffffff81413a15: alloc_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct aa_ns *alloc_ns(const char *prefix, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81445b40)
Location: security/apparmor/policy_ns.c:91
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff81445b40-ffffffff81445d05: alloc_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct aa_ns *alloc_ns(const char *prefix, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81462a60)
Location: security/apparmor/policy_ns.c:91
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff81462a60-ffffffff81462c21: alloc_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct aa_ns *alloc_ns(const char *prefix, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff8148fd90)
Location: security/apparmor/policy_ns.c:87
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff8148fd90-ffffffff8148ff63: alloc_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct aa_ns *alloc_ns(const char *prefix, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff814a9c50)
Location: security/apparmor/policy_ns.c:87
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff814a9c50-ffffffff814a9e23: alloc_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct aa_ns *alloc_ns(const char *prefix, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81507630)
Location: security/apparmor/policy_ns.c:87
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff81507630-ffffffff81507889: alloc_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct aa_ns *alloc_ns(const char *prefix, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff815246d0)
Location: security/apparmor/policy_ns.c:87
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff815246d0-ffffffff81524929: alloc_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct aa_ns *alloc_ns(const char *prefix, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff8152a810)
Location: security/apparmor/policy_ns.c:87
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff8152a810-ffffffff8152aa61: alloc_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct aa_ns *alloc_ns(const char *prefix, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (0)
Location: security/apparmor/policy_ns.c:87
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff81588bb0-ffffffff81588e0e: alloc_ns (STB_LOCAL)
ffffffff81cd66f5-ffffffff81cd6709: alloc_ns.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct aa_ns *alloc_ns(const char *prefix, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (0)
Location: security/apparmor/policy_ns.c:109
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff81629520-ffffffff81629691: alloc_ns (STB_LOCAL)
ffffffff81e89626-ffffffff81e8963b: alloc_ns.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct aa_ns *alloc_ns(const char *prefix, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff816ddb40)
Location: security/apparmor/policy_ns.c:106
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff816ddb40-ffffffff816ddcd7: alloc_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct aa_ns *alloc_ns(const char *prefix, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81717160)
Location: security/apparmor/policy_ns.c:106
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff81717160-ffffffff817172dc: alloc_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct aa_ns *alloc_ns(const char *prefix, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81755cc0)
Location: security/apparmor/policy_ns.c:106
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff81755cc0-ffffffff81755e6b: alloc_ns (STB_LOCAL)
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
struct aa_ns *alloc_ns(const char *prefix, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffff8000105a0630)
Location: security/apparmor/policy_ns.c:87
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffff8000105a0630-ffff8000105a07e8: alloc_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct aa_ns *alloc_ns(const char *prefix, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (c0751214)
Location: security/apparmor/policy_ns.c:87
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
c0751214-c07513e0: alloc_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct aa_ns *alloc_ns(const char *prefix, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (c00000000071a9f0)
Location: security/apparmor/policy_ns.c:87
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
c00000000071a9f0-c00000000071ac48: alloc_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct aa_ns *alloc_ns(const char *prefix, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffe0003eb59c)
Location: security/apparmor/policy_ns.c:87
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffe0003eb59c-ffffffe0003eb724: alloc_ns (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct aa_ns *alloc_ns(const char *prefix, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff814a2230)
Location: security/apparmor/policy_ns.c:87
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff814a2230-ffffffff814a2403: alloc_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct aa_ns *alloc_ns(const char *prefix, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81492c50)
Location: security/apparmor/policy_ns.c:87
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff81492c50-ffffffff81492e23: alloc_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct aa_ns *alloc_ns(const char *prefix, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff8149e2d0)
Location: security/apparmor/policy_ns.c:87
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff8149e2d0-ffffffff8149e4a3: alloc_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct aa_ns *alloc_ns(const char *prefix, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff814b68c0)
Location: security/apparmor/policy_ns.c:87
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff814b68c0-ffffffff814b6a93: alloc_ns (STB_LOCAL)
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

# Function: <code>aa_free_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void aa_free_ns(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81394840)
Location: security/apparmor/policy_ns.c:136
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
```
**Symbols:**

```
ffffffff81394840-ffffffff813948ae: aa_free_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void aa_free_ns(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff813d0020)
Location: security/apparmor/policy_ns.c:136
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff813d0020-ffffffff813d00bb: aa_free_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void aa_free_ns(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff813e7720)
Location: security/apparmor/policy_ns.c:137
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff813e7720-ffffffff813e77bb: aa_free_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aa_free_ns(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff813ec178)
Location: security/apparmor/policy_ns.c:141
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
Direct callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff813ec020-ffffffff813ec087: aa_free_ns.part.3 (STB_LOCAL)
ffffffff813ec260-ffffffff813ec277: aa_free_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aa_free_ns(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81413b14)
Location: security/apparmor/policy_ns.c:141
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
Direct callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff814137e0-ffffffff8141384b: aa_free_ns.part.3 (STB_LOCAL)
ffffffff81413bf0-ffffffff81413c07: aa_free_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void aa_free_ns(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81445db0)
Location: security/apparmor/policy_ns.c:141
Inline: True
Direct callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff81445db0-ffffffff81445e23: aa_free_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void aa_free_ns(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81462cd0)
Location: security/apparmor/policy_ns.c:141
Inline: True
Direct callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff81462cd0-ffffffff81462d43: aa_free_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aa_free_ns(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81490070)
Location: security/apparmor/policy_ns.c:137
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
Direct callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff8148fd10-ffffffff8148fd83: aa_free_ns.part.0 (STB_LOCAL)
ffffffff81490110-ffffffff81490126: aa_free_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aa_free_ns(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff814a9f30)
Location: security/apparmor/policy_ns.c:137
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
Direct callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff814a9bd0-ffffffff814a9c43: aa_free_ns.part.0 (STB_LOCAL)
ffffffff814a9fd0-ffffffff814a9fe6: aa_free_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aa_free_ns(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff815079c4)
Location: security/apparmor/policy_ns.c:137
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
Direct callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff815075a0-ffffffff81507628: aa_free_ns.part.0 (STB_LOCAL)
ffffffff81507ab0-ffffffff81507b3e: aa_free_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aa_free_ns(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81524a70)
Location: security/apparmor/policy_ns.c:137
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
Direct callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff81524640-ffffffff815246c8: aa_free_ns.part.0 (STB_LOCAL)
ffffffff81524b50-ffffffff81524bde: aa_free_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void aa_free_ns(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff8152abb0)
Location: security/apparmor/policy_ns.c:137
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff8152ad00-ffffffff8152ad8e: aa_free_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void aa_free_ns(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81588f50)
Location: security/apparmor/policy_ns.c:137
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff815890a0-ffffffff8158912e: aa_free_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aa_free_ns(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff8349c7e8)
Location: security/apparmor/policy_ns.c:152
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff816292d0-ffffffff8162935f: aa_free_ns.part.0 (STB_LOCAL)
ffffffff81629910-ffffffff81629932: aa_free_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aa_free_ns(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff83ed3eb0)
Location: security/apparmor/policy_ns.c:151
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff816ddcf0-ffffffff816ddd7f: aa_free_ns.part.0 (STB_LOCAL)
ffffffff816de040-ffffffff816de062: aa_free_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aa_free_ns(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff836f8ff0)
Location: security/apparmor/policy_ns.c:151
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff817172f0-ffffffff8171737f: aa_free_ns.part.0 (STB_LOCAL)
ffffffff81717640-ffffffff81717662: aa_free_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aa_free_ns(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff8392c400)
Location: security/apparmor/policy_ns.c:151
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff81755e80-ffffffff81755f0f: aa_free_ns.part.0 (STB_LOCAL)
ffffffff817561d0-ffffffff817561f2: aa_free_ns (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aa_free_ns(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffff8000105a0978)
Location: security/apparmor/policy_ns.c:137
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
Direct callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffff8000105a07e8-ffff8000105a0864: aa_free_ns.part.0 (STB_LOCAL)
ffff8000105a0ad8-ffff8000105a0b08: aa_free_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aa_free_ns(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (c0751544)
Location: security/apparmor/policy_ns.c:137
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
Direct callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
c07513e0-c075145c: aa_free_ns.part.0 (STB_LOCAL)
c0751640-c0751664: aa_free_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aa_free_ns(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (c00000000071aecc)
Location: security/apparmor/policy_ns.c:137
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
Direct callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
c00000000071ac50-c00000000071ad40: aa_free_ns.part.0 (STB_LOCAL)
c00000000071b030-c00000000071b04c: aa_free_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aa_free_ns(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffe0003eb880)
Location: security/apparmor/policy_ns.c:137
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
Direct callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffe0003eb724-ffffffe0003eb798: aa_free_ns.part.0 (STB_LOCAL)
ffffffe0003eb980-ffffffe0003eb9ac: aa_free_ns (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aa_free_ns(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff814a2510)
Location: security/apparmor/policy_ns.c:137
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
Direct callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff814a21b0-ffffffff814a2223: aa_free_ns.part.0 (STB_LOCAL)
ffffffff814a25b0-ffffffff814a25c6: aa_free_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aa_free_ns(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81492f30)
Location: security/apparmor/policy_ns.c:137
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
Direct callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff81492bd0-ffffffff81492c43: aa_free_ns.part.0 (STB_LOCAL)
ffffffff81492fd0-ffffffff81492fe6: aa_free_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aa_free_ns(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff8149e5b0)
Location: security/apparmor/policy_ns.c:137
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
Direct callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff8149e250-ffffffff8149e2c3: aa_free_ns.part.0 (STB_LOCAL)
ffffffff8149e650-ffffffff8149e666: aa_free_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aa_free_ns(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff814b6ba0)
Location: security/apparmor/policy_ns.c:137
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
Direct callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff814b6840-ffffffff814b68b3: aa_free_ns.part.0 (STB_LOCAL)
ffffffff814b6c40-ffffffff814b6c56: aa_free_ns (STB_GLOBAL)
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

# Function: <code>destroy_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void destroy_ns(struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81394c40)
Location: security/apparmor/policy_ns.c:250
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/policy_ns.c:aa_free_root_ns
```
**Symbols:**

```
ffffffff81394c40-ffffffff81394ce0: destroy_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void destroy_ns(struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff813d0660)
Location: security/apparmor/policy_ns.c:276
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
**Symbols:**

```
ffffffff813d0660-ffffffff813d0726: destroy_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void destroy_ns(struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff813e7d60)
Location: security/apparmor/policy_ns.c:277
Inline: False
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
**Symbols:**

```
ffffffff813e7d60-ffffffff813e7e26: destroy_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff820e4835)
Location: security/apparmor/policy_ns.c:334
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
**Symbols:**

```
ffffffff813ec650-ffffffff813ec70c: destroy_ns.part.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff826ed4d3)
Location: security/apparmor/policy_ns.c:334
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
**Symbols:**

```
ffffffff81413fe0-ffffffff8141409c: destroy_ns.part.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff8271782f)
Location: security/apparmor/policy_ns.c:334
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
**Symbols:**

```
ffffffff81446350-ffffffff81446407: destroy_ns.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff828cf287)
Location: security/apparmor/policy_ns.c:334
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
**Symbols:**

```
ffffffff81463270-ffffffff81463327: destroy_ns.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff828e8cef)
Location: security/apparmor/policy_ns.c:330
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
**Symbols:**

```
ffffffff81490530-ffffffff814905f0: destroy_ns.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff828f17db)
Location: security/apparmor/policy_ns.c:330
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
**Symbols:**

```
ffffffff814aa3f0-ffffffff814aa4b0: destroy_ns.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff82d0686c)
Location: security/apparmor/policy_ns.c:330
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
**Symbols:**

```
ffffffff815080c0-ffffffff81508180: destroy_ns.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff82ff3c37)
Location: security/apparmor/policy_ns.c:330
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
**Symbols:**

```
ffffffff815250c0-ffffffff81525180: destroy_ns.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff831fe755)
Location: security/apparmor/policy_ns.c:330
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
**Symbols:**

```
ffffffff8152b270-ffffffff8152b330: destroy_ns.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff832e5a67)
Location: security/apparmor/policy_ns.c:330
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
**Symbols:**

```
ffffffff81589610-ffffffff815896d0: destroy_ns.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff8349c851)
Location: security/apparmor/policy_ns.c:345
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
**Symbols:**

```
ffffffff81629e90-ffffffff81629f58: destroy_ns.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff83ed3f08)
Location: security/apparmor/policy_ns.c:344
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
**Symbols:**

```
ffffffff816de6d0-ffffffff816de798: destroy_ns.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff836f9048)
Location: security/apparmor/policy_ns.c:344
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
**Symbols:**

```
ffffffff81717cd0-ffffffff81717d98: destroy_ns.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff8392c458)
Location: security/apparmor/policy_ns.c:307
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
**Symbols:**

```
ffffffff817566a0-ffffffff81756768: destroy_ns.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffff80001146ba04)
Location: security/apparmor/policy_ns.c:330
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
**Symbols:**

```
ffff8000105a1058-ffff8000105a1178: destroy_ns.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (c154466c)
Location: security/apparmor/policy_ns.c:330
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
**Symbols:**

```
c0751a88-c0751b3c: destroy_ns.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (c00000000139a57c)
Location: security/apparmor/policy_ns.c:330
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
**Symbols:**

```
c00000000071b800-c00000000071b910: destroy_ns.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffe0000269f8)
Location: security/apparmor/policy_ns.c:330
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
**Symbols:**

```
ffffffe0003ebd78-ffffffe0003ebe36: destroy_ns.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff828da68f)
Location: security/apparmor/policy_ns.c:330
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
**Symbols:**

```
ffffffff814a29d0-ffffffff814a2a90: destroy_ns.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff828d2dab)
Location: security/apparmor/policy_ns.c:330
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
**Symbols:**

```
ffffffff814933f0-ffffffff814934b0: destroy_ns.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff828ed403)
Location: security/apparmor/policy_ns.c:330
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
**Symbols:**

```
ffffffff8149ea70-ffffffff8149eb30: destroy_ns.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff828f2825)
Location: security/apparmor/policy_ns.c:330
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
**Symbols:**

```
ffffffff814b70a0-ffffffff814b7160: destroy_ns.part.0 (STB_LOCAL)
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
</ul>

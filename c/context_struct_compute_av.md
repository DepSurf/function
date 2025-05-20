# Function: <code>context_struct_compute_av</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void context_struct_compute_av(struct context *scontext, struct context *tcontext, u16 tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81356e90)
Location: security/selinux/ss/services.c:648
Inline: False
Direct callers:
  - security/selinux/ss/services.c:type_attribute_bounds_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av_user
```
**Symbols:**

```
ffffffff81356e90-ffffffff813572ed: context_struct_compute_av (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void context_struct_compute_av(struct context *scontext, struct context *tcontext, u16 tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138d160)
Location: security/selinux/ss/services.c:622
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
```
**Symbols:**

```
ffffffff8138d160-ffffffff8138d5bb: context_struct_compute_av (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void context_struct_compute_av(struct context *scontext, struct context *tcontext, u16 tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a3d70)
Location: security/selinux/ss/services.c:622
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
```
**Symbols:**

```
ffffffff813a3d70-ffffffff813a41cb: context_struct_compute_av (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void context_struct_compute_av(struct context *scontext, struct context *tcontext, u16 tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813ba790)
Location: security/selinux/ss/services.c:634
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
```
**Symbols:**

```
ffffffff813ba790-ffffffff813babbf: context_struct_compute_av (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void context_struct_compute_av(struct context *scontext, struct context *tcontext, u16 tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e08f0)
Location: security/selinux/ss/services.c:636
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
```
**Symbols:**

```
ffffffff813e08f0-ffffffff813e0d1f: context_struct_compute_av (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void context_struct_compute_av(struct policydb *policydb, struct context *scontext, struct context *tcontext, u16 tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:621
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
```
**Symbols:**

```
ffffffff81410f10-ffffffff8141136e: context_struct_compute_av (STB_LOCAL)
ffffffff81414bd4-ffffffff81414be9: context_struct_compute_av.cold.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void context_struct_compute_av(struct policydb *policydb, struct context *scontext, struct context *tcontext, u16 tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:618
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
```
**Symbols:**

```
ffffffff8142d400-ffffffff8142d85e: context_struct_compute_av (STB_LOCAL)
ffffffff8143118a-ffffffff8143119f: context_struct_compute_av.cold.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void context_struct_compute_av(struct policydb *policydb, struct context *scontext, struct context *tcontext, u16 tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:613
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
```
**Symbols:**

```
ffffffff8145aca0-ffffffff8145b155: context_struct_compute_av (STB_LOCAL)
ffffffff8145ec1e-ffffffff8145ec36: context_struct_compute_av.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void context_struct_compute_av(struct policydb *policydb, struct context *scontext, struct context *tcontext, u16 tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:613
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
```
**Symbols:**

```
ffffffff81474a50-ffffffff81474f05: context_struct_compute_av (STB_LOCAL)
ffffffff814789d0-ffffffff814789e8: context_struct_compute_av.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void context_struct_compute_av(struct policydb *policydb, struct context *scontext, struct context *tcontext, u16 tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:618
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
```
**Symbols:**

```
ffffffff814ca2c0-ffffffff814ca75f: context_struct_compute_av (STB_LOCAL)
ffffffff814cde87-ffffffff814cde9f: context_struct_compute_av.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void context_struct_compute_av(struct policydb *policydb, struct context *scontext, struct context *tcontext, u16 tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:617
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
```
**Symbols:**

```
ffffffff814e7be0-ffffffff814e807f: context_struct_compute_av (STB_LOCAL)
ffffffff81bf0efa-ffffffff81bf0f12: context_struct_compute_av.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void context_struct_compute_av(struct policydb *policydb, struct context *scontext, struct context *tcontext, u16 tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:619
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
```
**Symbols:**

```
ffffffff814ee3c0-ffffffff814ee873: context_struct_compute_av (STB_LOCAL)
ffffffff81be301c-ffffffff81be3034: context_struct_compute_av.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void context_struct_compute_av(struct policydb *policydb, struct context *scontext, struct context *tcontext, u16 tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:619
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
```
**Symbols:**

```
ffffffff81548880-ffffffff81548d33: context_struct_compute_av (STB_LOCAL)
ffffffff81cd4d31-ffffffff81cd4d49: context_struct_compute_av.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void context_struct_compute_av(struct policydb *policydb, struct context *scontext, struct context *tcontext, u16 tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:617
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
```
**Symbols:**

```
ffffffff815e12b0-ffffffff815e17ab: context_struct_compute_av (STB_LOCAL)
ffffffff81e87c48-ffffffff81e87c5d: context_struct_compute_av.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void context_struct_compute_av(struct policydb *policydb, struct context *scontext, struct context *tcontext, u16 tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8168fe90)
Location: security/selinux/ss/services.c:611
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
```
**Symbols:**

```
ffffffff8168fe90-ffffffff81690389: context_struct_compute_av (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void context_struct_compute_av(struct policydb *policydb, struct context *scontext, struct context *tcontext, u16 tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816c8340)
Location: security/selinux/ss/services.c:611
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
```
**Symbols:**

```
ffffffff816c8340-ffffffff816c884a: context_struct_compute_av (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void context_struct_compute_av(struct policydb *policydb, struct context *scontext, struct context *tcontext, u16 tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81704f50)
Location: security/selinux/ss/services.c:611
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
```
**Symbols:**

```
ffffffff81704f50-ffffffff8170545a: context_struct_compute_av (STB_LOCAL)
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
void context_struct_compute_av(struct policydb *policydb, struct context *scontext, struct context *tcontext, u16 tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff800010563f00)
Location: security/selinux/ss/services.c:613
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
```
**Symbols:**

```
ffff800010563f00-ffff800010564394: context_struct_compute_av (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void context_struct_compute_av(struct policydb *policydb, struct context *scontext, struct context *tcontext, u16 tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0718a30)
Location: security/selinux/ss/services.c:613
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
```
**Symbols:**

```
c0718a30-c0718f08: context_struct_compute_av (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void context_struct_compute_av(struct policydb *policydb, struct context *scontext, struct context *tcontext, u16 tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c6420)
Location: security/selinux/ss/services.c:613
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
```
**Symbols:**

```
c0000000006c6420-c0000000006c6a38: context_struct_compute_av (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void context_struct_compute_av(struct policydb *policydb, struct context *scontext, struct context *tcontext, u16 tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003ba8ee)
Location: security/selinux/ss/services.c:613
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
```
**Symbols:**

```
ffffffe0003ba8ee-ffffffe0003bad24: context_struct_compute_av (STB_LOCAL)
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
void context_struct_compute_av(struct policydb *policydb, struct context *scontext, struct context *tcontext, u16 tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:613
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
```
**Symbols:**

```
ffffffff8146d030-ffffffff8146d4e5: context_struct_compute_av (STB_LOCAL)
ffffffff81470fb0-ffffffff81470fc8: context_struct_compute_av.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void context_struct_compute_av(struct policydb *policydb, struct context *scontext, struct context *tcontext, u16 tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:613
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
```
**Symbols:**

```
ffffffff8145da60-ffffffff8145df15: context_struct_compute_av (STB_LOCAL)
ffffffff814619d0-ffffffff814619e8: context_struct_compute_av.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void context_struct_compute_av(struct policydb *policydb, struct context *scontext, struct context *tcontext, u16 tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:613
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
```
**Symbols:**

```
ffffffff814690d0-ffffffff81469585: context_struct_compute_av (STB_LOCAL)
ffffffff8146d050-ffffffff8146d068: context_struct_compute_av.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void context_struct_compute_av(struct policydb *policydb, struct context *scontext, struct context *tcontext, u16 tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:613
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
```
**Symbols:**

```
ffffffff81480890-ffffffff81480d45: context_struct_compute_av (STB_LOCAL)
ffffffff814848bc-ffffffff814848d4: context_struct_compute_av.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct policydb *policydb</code>
</li>
<li>
<b>Param reordered. </b>
<code>scontext, tcontext, tclass, avd, xperms</code> ➡️ <code>policydb, scontext, tcontext, tclass, avd, xperms</code>
</li>
</ul>
</details>
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

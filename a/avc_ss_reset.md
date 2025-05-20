# Function: <code>avc_ss_reset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int avc_ss_reset(u32 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81340eb0)
Location: security/selinux/avc.c:940
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_set_bools
```
**Symbols:**

```
ffffffff81340eb0-ffffffff81340f32: avc_ss_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int avc_ss_reset(u32 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81376560)
Location: security/selinux/avc.c:940
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81376560-ffffffff813765e2: avc_ss_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int avc_ss_reset(u32 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8138ce90)
Location: security/selinux/avc.c:940
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff8138ce90-ffffffff8138cf12: avc_ss_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int avc_ss_reset(u32 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813a2bc0)
Location: security/selinux/avc.c:940
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff813a2bc0-ffffffff813a2c37: avc_ss_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int avc_ss_reset(u32 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813c89c0)
Location: security/selinux/avc.c:936
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff813c89c0-ffffffff813c8a3d: avc_ss_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int avc_ss_reset(struct selinux_avc *avc, u32 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813f8080)
Location: security/selinux/avc.c:968
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff813f8080-ffffffff813f8104: avc_ss_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int avc_ss_reset(struct selinux_avc *avc, u32 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81413b30)
Location: security/selinux/avc.c:968
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81413b30-ffffffff81413bb4: avc_ss_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int avc_ss_reset(struct selinux_avc *avc, u32 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81441620)
Location: security/selinux/avc.c:980
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81441620-ffffffff814416a4: avc_ss_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int avc_ss_reset(struct selinux_avc *avc, u32 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8145aef0)
Location: security/selinux/avc.c:964
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff8145aef0-ffffffff8145af74: avc_ss_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int avc_ss_reset(struct selinux_avc *avc, u32 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814ae200)
Location: security/selinux/avc.c:964
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff814ae200-ffffffff814ae284: avc_ss_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int avc_ss_reset(struct selinux_avc *avc, u32 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814cbcb0)
Location: security/selinux/avc.c:971
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:selinux_notify_policy_change
```
**Symbols:**

```
ffffffff814cbcb0-ffffffff814cbd34: avc_ss_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int avc_ss_reset(struct selinux_avc *avc, u32 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814d22e0)
Location: security/selinux/avc.c:972
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:selinux_notify_policy_change
```
**Symbols:**

```
ffffffff814d22e0-ffffffff814d2364: avc_ss_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int avc_ss_reset(struct selinux_avc *avc, u32 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8152b150)
Location: security/selinux/avc.c:961
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:selinux_notify_policy_change
```
**Symbols:**

```
ffffffff8152b150-ffffffff8152b1d4: avc_ss_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int avc_ss_reset(struct selinux_avc *avc, u32 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff815c0bd0)
Location: security/selinux/avc.c:970
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:selinux_notify_policy_change
```
**Symbols:**

```
ffffffff815c0bd0-ffffffff815c0c5c: avc_ss_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int avc_ss_reset(struct selinux_avc *avc, u32 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8166d1d0)
Location: security/selinux/avc.c:970
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:selinux_notify_policy_change
```
**Symbols:**

```
ffffffff8166d1d0-ffffffff8166d25c: avc_ss_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int avc_ss_reset(u32 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff816a5830)
Location: security/selinux/avc.c:951
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:selinux_notify_policy_change
```
**Symbols:**

```
ffffffff816a5830-ffffffff816a59a0: avc_ss_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int avc_ss_reset(u32 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff816e2270)
Location: security/selinux/avc.c:952
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:selinux_notify_policy_change
```
**Symbols:**

```
ffffffff816e2270-ffffffff816e23e0: avc_ss_reset (STB_GLOBAL)
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
int avc_ss_reset(struct selinux_avc *avc, u32 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffff8000105477e8)
Location: security/selinux/avc.c:964
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffff8000105477e8-ffff8000105478e8: avc_ss_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int avc_ss_reset(struct selinux_avc *avc, u32 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (c06fd424)
Location: security/selinux/avc.c:964
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
c06fd424-c06fd4c0: avc_ss_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int avc_ss_reset(struct selinux_avc *avc, u32 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (c00000000069e720)
Location: security/selinux/avc.c:964
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
c00000000069e720-c00000000069e800: avc_ss_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int avc_ss_reset(struct selinux_avc *avc, u32 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffe0003a2e4a)
Location: security/selinux/avc.c:964
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffe0003a2e4a-ffffffe0003a2ed8: avc_ss_reset (STB_GLOBAL)
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
int avc_ss_reset(struct selinux_avc *avc, u32 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814534d0)
Location: security/selinux/avc.c:964
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff814534d0-ffffffff81453554: avc_ss_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int avc_ss_reset(struct selinux_avc *avc, u32 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81443f10)
Location: security/selinux/avc.c:964
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81443f10-ffffffff81443f94: avc_ss_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int avc_ss_reset(struct selinux_avc *avc, u32 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8144f570)
Location: security/selinux/avc.c:964
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff8144f570-ffffffff8144f5f4: avc_ss_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int avc_ss_reset(struct selinux_avc *avc, u32 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814669a0)
Location: security/selinux/avc.c:964
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff814669a0-ffffffff81466a24: avc_ss_reset (STB_GLOBAL)
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
<code>struct selinux_avc *avc</code>
</li>
<li>
<b>Param reordered. </b>
<code>seqno</code> ➡️ <code>avc, seqno</code>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct selinux_avc *avc</code>
</li>
<li>
<b>Param reordered. </b>
<code>avc, seqno</code> ➡️ <code>seqno</code>
</li>
</ul>
</details>
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

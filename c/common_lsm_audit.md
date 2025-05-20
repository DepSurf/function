# Function: <code>common_lsm_audit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void common_lsm_audit(struct common_audit_data *a, void (*pre_audit)(struct audit_buffer *, void *), void (*post_audit)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff81366400)
Location: security/lsm_audit.c:412
Inline: False
Direct callers:
  - security/selinux/avc.c:slow_avc_audit
  - security/smack/smack_access.c:smack_log
  - security/apparmor/audit.c:aa_audit
```
**Symbols:**

```
ffffffff81366400-ffffffff81366b36: common_lsm_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void common_lsm_audit(struct common_audit_data *a, void (*pre_audit)(struct audit_buffer *, void *), void (*post_audit)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff8139c4e0)
Location: security/lsm_audit.c:412
Inline: False
Direct callers:
  - security/selinux/avc.c:slow_avc_audit
  - security/smack/smack_access.c:smack_log
  - security/apparmor/audit.c:aa_audit
```
**Symbols:**

```
ffffffff8139c4e0-ffffffff8139cbd7: common_lsm_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void common_lsm_audit(struct common_audit_data *a, void (*pre_audit)(struct audit_buffer *, void *), void (*post_audit)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff813b3090)
Location: security/lsm_audit.c:425
Inline: False
Direct callers:
  - security/selinux/avc.c:slow_avc_audit
  - security/smack/smack_access.c:smack_log
  - security/apparmor/audit.c:aa_audit
```
**Symbols:**

```
ffffffff813b3090-ffffffff813b37be: common_lsm_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void common_lsm_audit(struct common_audit_data *a, void (*pre_audit)(struct audit_buffer *, void *), void (*post_audit)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff813c9a50)
Location: security/lsm_audit.c:441
Inline: False
Direct callers:
  - security/selinux/avc.c:slow_avc_audit
  - security/smack/smack_access.c:smack_log
  - security/apparmor/audit.c:aa_audit
```
**Symbols:**

```
ffffffff813c9a50-ffffffff813ca18b: common_lsm_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void common_lsm_audit(struct common_audit_data *a, void (*pre_audit)(struct audit_buffer *, void *), void (*post_audit)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff813efee0)
Location: security/lsm_audit.c:441
Inline: False
Direct callers:
  - security/selinux/avc.c:slow_avc_audit
  - security/smack/smack_access.c:smack_log
  - security/apparmor/audit.c:aa_audit
```
**Symbols:**

```
ffffffff813efee0-ffffffff813f0625: common_lsm_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void common_lsm_audit(struct common_audit_data *a, void (*pre_audit)(struct audit_buffer *, void *), void (*post_audit)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff814214a0)
Location: security/lsm_audit.c:441
Inline: False
Direct callers:
  - security/selinux/avc.c:slow_avc_audit
  - security/smack/smack_access.c:smack_log
  - security/apparmor/audit.c:aa_audit
```
**Symbols:**

```
ffffffff814214a0-ffffffff81421522: common_lsm_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void common_lsm_audit(struct common_audit_data *a, void (*pre_audit)(struct audit_buffer *, void *), void (*post_audit)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff8143db20)
Location: security/lsm_audit.c:443
Inline: False
Direct callers:
  - security/selinux/avc.c:slow_avc_audit
  - security/smack/smack_access.c:smack_log
  - security/apparmor/audit.c:aa_audit
```
**Symbols:**

```
ffffffff8143db20-ffffffff8143dba2: common_lsm_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void common_lsm_audit(struct common_audit_data *a, void (*pre_audit)(struct audit_buffer *, void *), void (*post_audit)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff8146b6e0)
Location: security/lsm_audit.c:440
Inline: False
Direct callers:
  - security/selinux/avc.c:slow_avc_audit
  - security/smack/smack_access.c:smack_log
  - security/apparmor/audit.c:aa_audit
```
**Symbols:**

```
ffffffff8146b6e0-ffffffff8146b762: common_lsm_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void common_lsm_audit(struct common_audit_data *a, void (*pre_audit)(struct audit_buffer *, void *), void (*post_audit)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff814854c0)
Location: security/lsm_audit.c:440
Inline: False
Direct callers:
  - security/selinux/avc.c:slow_avc_audit
  - security/smack/smack_access.c:smack_log
  - security/apparmor/audit.c:aa_audit
```
**Symbols:**

```
ffffffff814854c0-ffffffff81485542: common_lsm_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void common_lsm_audit(struct common_audit_data *a, void (*pre_audit)(struct audit_buffer *, void *), void (*post_audit)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff814db670)
Location: security/lsm_audit.c:445
Inline: False
Direct callers:
  - security/selinux/avc.c:slow_avc_audit
  - security/smack/smack_access.c:smack_log
  - security/apparmor/audit.c:aa_audit
```
**Symbols:**

```
ffffffff814db670-ffffffff814db6f2: common_lsm_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void common_lsm_audit(struct common_audit_data *a, void (*pre_audit)(struct audit_buffer *, void *), void (*post_audit)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff814f8b00)
Location: security/lsm_audit.c:448
Inline: False
Direct callers:
  - security/selinux/avc.c:slow_avc_audit
  - security/smack/smack_access.c:smack_log
  - security/apparmor/audit.c:aa_audit
```
**Symbols:**

```
ffffffff814f8b00-ffffffff814f8b82: common_lsm_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void common_lsm_audit(struct common_audit_data *a, void (*pre_audit)(struct audit_buffer *, void *), void (*post_audit)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff814ff890)
Location: security/lsm_audit.c:449
Inline: False
Direct callers:
  - security/selinux/avc.c:slow_avc_audit
  - security/smack/smack_access.c:smack_log
  - security/apparmor/audit.c:aa_audit
```
**Symbols:**

```
ffffffff814ff890-ffffffff814ff912: common_lsm_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void common_lsm_audit(struct common_audit_data *a, void (*pre_audit)(struct audit_buffer *, void *), void (*post_audit)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff8155a900)
Location: security/lsm_audit.c:448
Inline: False
Direct callers:
  - security/selinux/avc.c:slow_avc_audit
  - security/smack/smack_access.c:smack_log
  - security/apparmor/audit.c:aa_audit
```
**Symbols:**

```
ffffffff8155a900-ffffffff8155a982: common_lsm_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void common_lsm_audit(struct common_audit_data *a, void (*pre_audit)(struct audit_buffer *, void *), void (*post_audit)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff815f56b0)
Location: security/lsm_audit.c:451
Inline: False
Direct callers:
  - security/selinux/avc.c:slow_avc_audit
  - security/smack/smack_access.c:smack_log
  - security/apparmor/audit.c:aa_audit
```
**Symbols:**

```
ffffffff815f56b0-ffffffff815f5750: common_lsm_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void common_lsm_audit(struct common_audit_data *a, void (*pre_audit)(struct audit_buffer *, void *), void (*post_audit)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff816a61a0)
Location: security/lsm_audit.c:440
Inline: False
Direct callers:
  - security/selinux/avc.c:slow_avc_audit
  - security/smack/smack_access.c:smack_log
  - security/apparmor/audit.c:aa_audit
```
**Symbols:**

```
ffffffff816a61a0-ffffffff816a6240: common_lsm_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void common_lsm_audit(struct common_audit_data *a, void (*pre_audit)(struct audit_buffer *, void *), void (*post_audit)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff816deb80)
Location: security/lsm_audit.c:440
Inline: False
Direct callers:
  - security/selinux/avc.c:slow_avc_audit
  - security/smack/smack_access.c:smack_log
  - security/apparmor/audit.c:aa_audit
```
**Symbols:**

```
ffffffff816deb80-ffffffff816dec20: common_lsm_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void common_lsm_audit(struct common_audit_data *a, void (*pre_audit)(struct audit_buffer *, void *), void (*post_audit)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff8171b750)
Location: security/lsm_audit.c:440
Inline: False
Direct callers:
  - security/selinux/avc.c:slow_avc_audit
  - security/smack/smack_access.c:smack_log
  - security/apparmor/audit.c:aa_audit
```
**Symbols:**

```
ffffffff8171b750-ffffffff8171b7f0: common_lsm_audit (STB_GLOBAL)
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
void common_lsm_audit(struct common_audit_data *a, void (*pre_audit)(struct audit_buffer *, void *), void (*post_audit)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffff8000105779f8)
Location: security/lsm_audit.c:440
Inline: False
Direct callers:
  - security/selinux/avc.c:slow_avc_audit
  - security/smack/smack_access.c:smack_log
  - security/apparmor/audit.c:aa_audit
```
**Symbols:**

```
ffff8000105779f8-ffff800010577a7c: common_lsm_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void common_lsm_audit(struct common_audit_data *a, void (*pre_audit)(struct audit_buffer *, void *), void (*post_audit)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (c072a838)
Location: security/lsm_audit.c:440
Inline: False
Direct callers:
  - security/selinux/avc.c:slow_avc_audit
  - security/smack/smack_access.c:smack_log
  - security/apparmor/audit.c:aa_audit
```
**Symbols:**

```
c072a838-c072a8c0: common_lsm_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void common_lsm_audit(struct common_audit_data *a, void (*pre_audit)(struct audit_buffer *, void *), void (*post_audit)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (c0000000006e1110)
Location: security/lsm_audit.c:440
Inline: False
Direct callers:
  - security/selinux/avc.c:slow_avc_audit
  - security/smack/smack_access.c:smack_log
  - security/apparmor/audit.c:aa_audit
  - security/apparmor/audit.c:aa_audit
```
**Symbols:**

```
c0000000006e1110-c0000000006e11e4: common_lsm_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void common_lsm_audit(struct common_audit_data *a, void (*pre_audit)(struct audit_buffer *, void *), void (*post_audit)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffe0003c9ec8)
Location: security/lsm_audit.c:440
Inline: False
Direct callers:
  - security/selinux/avc.c:slow_avc_audit
  - security/smack/smack_access.c:smack_log
  - security/apparmor/audit.c:aa_audit
```
**Symbols:**

```
ffffffe0003c9ec8-ffffffe0003c9f3c: common_lsm_audit (STB_GLOBAL)
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
void common_lsm_audit(struct common_audit_data *a, void (*pre_audit)(struct audit_buffer *, void *), void (*post_audit)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff8147daa0)
Location: security/lsm_audit.c:440
Inline: False
Direct callers:
  - security/selinux/avc.c:slow_avc_audit
  - security/smack/smack_access.c:smack_log
  - security/apparmor/audit.c:aa_audit
```
**Symbols:**

```
ffffffff8147daa0-ffffffff8147db22: common_lsm_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void common_lsm_audit(struct common_audit_data *a, void (*pre_audit)(struct audit_buffer *, void *), void (*post_audit)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff8146e4c0)
Location: security/lsm_audit.c:440
Inline: False
Direct callers:
  - security/selinux/avc.c:slow_avc_audit
  - security/smack/smack_access.c:smack_log
  - security/apparmor/audit.c:aa_audit
```
**Symbols:**

```
ffffffff8146e4c0-ffffffff8146e542: common_lsm_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void common_lsm_audit(struct common_audit_data *a, void (*pre_audit)(struct audit_buffer *, void *), void (*post_audit)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff81479b40)
Location: security/lsm_audit.c:440
Inline: False
Direct callers:
  - security/selinux/avc.c:slow_avc_audit
  - security/smack/smack_access.c:smack_log
  - security/apparmor/audit.c:aa_audit
```
**Symbols:**

```
ffffffff81479b40-ffffffff81479bc2: common_lsm_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void common_lsm_audit(struct common_audit_data *a, void (*pre_audit)(struct audit_buffer *, void *), void (*post_audit)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff814915f0)
Location: security/lsm_audit.c:440
Inline: False
Direct callers:
  - security/selinux/avc.c:slow_avc_audit
  - security/smack/smack_access.c:smack_log
  - security/apparmor/audit.c:aa_audit
```
**Symbols:**

```
ffffffff814915f0-ffffffff81491672: common_lsm_audit (STB_GLOBAL)
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

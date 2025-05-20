# Function: <code>policy_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t policy_update(u32 mask, const char *buf, size_t size, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81375e80)
Location: security/apparmor/apparmorfs.c:113
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
**Symbols:**

```
ffffffff81375e80-ffffffff8137606e: policy_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t policy_update(u32 mask, const char *buf, size_t size, loff_t *pos, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813ad050)
Location: security/apparmor/apparmorfs.c:121
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:profile_load
```
**Symbols:**

```
ffffffff813ad050-ffffffff813ad304: policy_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t policy_update(u32 mask, const char *buf, size_t size, loff_t *pos, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813c3e60)
Location: security/apparmor/apparmorfs.c:121
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:profile_load
```
**Symbols:**

```
ffffffff813c3e60-ffffffff813c4114: policy_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t policy_update(u32 mask, const char *buf, size_t size, loff_t *pos, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813daa20)
Location: security/apparmor/apparmorfs.c:409
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:profile_load
```
**Symbols:**

```
ffffffff813daa20-ffffffff813dab9d: policy_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t policy_update(u32 mask, const char *buf, size_t size, loff_t *pos, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81400ec0)
Location: security/apparmor/apparmorfs.c:410
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:profile_load
```
**Symbols:**

```
ffffffff81400ec0-ffffffff8140107a: policy_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t policy_update(u32 mask, const char *buf, size_t size, loff_t *pos, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814314f0)
Location: security/apparmor/apparmorfs.c:407
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:profile_load
```
**Symbols:**

```
ffffffff814314f0-ffffffff81431695: policy_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t policy_update(u32 mask, const char *buf, size_t size, loff_t *pos, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8144ea70)
Location: security/apparmor/apparmorfs.c:408
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:profile_load
```
**Symbols:**

```
ffffffff8144ea70-ffffffff8144ec34: policy_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t policy_update(u32 mask, const char *buf, size_t size, loff_t *pos, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8147c300)
Location: security/apparmor/apparmorfs.c:413
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:profile_load
```
**Symbols:**

```
ffffffff8147c300-ffffffff8147c4a6: policy_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t policy_update(u32 mask, const char *buf, size_t size, loff_t *pos, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81495fd0)
Location: security/apparmor/apparmorfs.c:381
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:profile_load
```
**Symbols:**

```
ffffffff81495fd0-ffffffff81496176: policy_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t policy_update(u32 mask, const char *buf, size_t size, loff_t *pos, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814ee280)
Location: security/apparmor/apparmorfs.c:411
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:profile_load
```
**Symbols:**

```
ffffffff814ee280-ffffffff814ee3cc: policy_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t policy_update(u32 mask, const char *buf, size_t size, loff_t *pos, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8150b910)
Location: security/apparmor/apparmorfs.c:411
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:profile_load
```
**Symbols:**

```
ffffffff8150b910-ffffffff8150ba5c: policy_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t policy_update(u32 mask, const char *buf, size_t size, loff_t *pos, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff815122a0)
Location: security/apparmor/apparmorfs.c:411
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:profile_load
```
**Symbols:**

```
ffffffff815122a0-ffffffff815123ec: policy_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t policy_update(u32 mask, const char *buf, size_t size, loff_t *pos, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8156fea0)
Location: security/apparmor/apparmorfs.c:411
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:profile_load
```
**Symbols:**

```
ffffffff8156fea0-ffffffff8156ffec: policy_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t policy_update(u32 mask, const char *buf, size_t size, loff_t *pos, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8160bf50)
Location: security/apparmor/apparmorfs.c:414
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:profile_load
```
**Symbols:**

```
ffffffff8160bf50-ffffffff8160c0b8: policy_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t policy_update(u32 mask, const char *buf, size_t size, loff_t *pos, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816be5f0)
Location: security/apparmor/apparmorfs.c:415
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:profile_load
```
**Symbols:**

```
ffffffff816be5f0-ffffffff816be768: policy_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t policy_update(u32 mask, const char *buf, size_t size, loff_t *pos, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816f70b0)
Location: security/apparmor/apparmorfs.c:416
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:profile_load
```
**Symbols:**

```
ffffffff816f70b0-ffffffff816f7228: policy_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t policy_update(u32 mask, const char *buf, size_t size, loff_t *pos, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81733e20)
Location: security/apparmor/apparmorfs.c:416
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:profile_load
```
**Symbols:**

```
ffffffff81733e20-ffffffff81733f9b: policy_update (STB_LOCAL)
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
ssize_t policy_update(u32 mask, const char *buf, size_t size, loff_t *pos, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffff80001058c2c0)
Location: security/apparmor/apparmorfs.c:381
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:profile_load
```
**Symbols:**

```
ffff80001058c2c0-ffff80001058c470: policy_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t policy_update(u32 mask, const char *buf, size_t size, loff_t *pos, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (c073ce64)
Location: security/apparmor/apparmorfs.c:381
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:profile_load
```
**Symbols:**

```
c073ce64-c073d02c: policy_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t policy_update(u32 mask, const char *buf, size_t size, loff_t *pos, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (c0000000006fddd0)
Location: security/apparmor/apparmorfs.c:381
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:profile_load
```
**Symbols:**

```
c0000000006fddd0-c0000000006fe080: policy_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t policy_update(u32 mask, const char *buf, size_t size, loff_t *pos, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffe0003da784)
Location: security/apparmor/apparmorfs.c:381
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:profile_load
```
**Symbols:**

```
ffffffe0003da784-ffffffe0003da8de: policy_update (STB_LOCAL)
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
ssize_t policy_update(u32 mask, const char *buf, size_t size, loff_t *pos, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8148e5b0)
Location: security/apparmor/apparmorfs.c:381
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:profile_load
```
**Symbols:**

```
ffffffff8148e5b0-ffffffff8148e756: policy_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t policy_update(u32 mask, const char *buf, size_t size, loff_t *pos, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8147efd0)
Location: security/apparmor/apparmorfs.c:381
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:profile_load
```
**Symbols:**

```
ffffffff8147efd0-ffffffff8147f176: policy_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t policy_update(u32 mask, const char *buf, size_t size, loff_t *pos, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8148a650)
Location: security/apparmor/apparmorfs.c:381
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:profile_load
```
**Symbols:**

```
ffffffff8148a650-ffffffff8148a7f6: policy_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t policy_update(u32 mask, const char *buf, size_t size, loff_t *pos, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814a2330)
Location: security/apparmor/apparmorfs.c:381
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:profile_load
```
**Symbols:**

```
ffffffff814a2330-ffffffff814a24f1: policy_update (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct aa_ns *ns</code>
</li>
</ul>
</details>
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

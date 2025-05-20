# Function: <code>__labelset_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8138dce3)
Location: security/apparmor/label.c:2037
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813c8ae3)
Location: security/apparmor/label.c:2065
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813e00f7)
Location: security/apparmor/label.c:2102
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813ef5f2)
Location: security/apparmor/label.c:2082
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81417412)
Location: security/apparmor/label.c:2082
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81449855)
Location: security/apparmor/label.c:2095
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814667e5)
Location: security/apparmor/label.c:2096
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __labelset_update(struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814917b0)
Location: security/apparmor/label.c:2092
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
**Symbols:**

```
ffffffff814917b0-ffffffff81491bc7: __labelset_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __labelset_update(struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814ab6e0)
Location: security/apparmor/label.c:2121
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
**Symbols:**

```
ffffffff814ab6e0-ffffffff814abaf7: __labelset_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8150cb65)
Location: security/apparmor/label.c:2118
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81529a25)
Location: security/apparmor/label.c:2118
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __labelset_update(struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8152cf70)
Location: security/apparmor/label.c:2118
Inline: False
```
**Symbols:**

```
ffffffff8152cf70-ffffffff8152d13a: __labelset_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __labelset_update(struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8158b360)
Location: security/apparmor/label.c:2118
Inline: False
```
**Symbols:**

```
ffffffff8158b360-ffffffff8158b52a: __labelset_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __labelset_update(struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8162c8c0)
Location: security/apparmor/label.c:2128
Inline: False
```
**Symbols:**

```
ffffffff8162c8c0-ffffffff8162caaa: __labelset_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __labelset_update(struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff816e1370)
Location: security/apparmor/label.c:2122
Inline: False
```
**Symbols:**

```
ffffffff816e1370-ffffffff816e155a: __labelset_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __labelset_update(struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8171a970)
Location: security/apparmor/label.c:2122
Inline: False
```
**Symbols:**

```
ffffffff8171a970-ffffffff8171ab52: __labelset_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __labelset_update(struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81759420)
Location: security/apparmor/label.c:2129
Inline: False
```
**Symbols:**

```
ffffffff81759420-ffffffff81759602: __labelset_update (STB_LOCAL)
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
void __labelset_update(struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffff8000105a2a60)
Location: security/apparmor/label.c:2121
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
**Symbols:**

```
ffff8000105a2a60-ffff8000105a2ef4: __labelset_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __labelset_update(struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c0752d74)
Location: security/apparmor/label.c:2121
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
**Symbols:**

```
c0752d74-c0753100: __labelset_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __labelset_update(struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c00000000071da40)
Location: security/apparmor/label.c:2121
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
**Symbols:**

```
c00000000071da40-c00000000071dfb8: __labelset_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __labelset_update(struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffe0003ed096)
Location: security/apparmor/label.c:2121
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
**Symbols:**

```
ffffffe0003ed096-ffffffe0003ed410: __labelset_update (STB_LOCAL)
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
void __labelset_update(struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814a3cc0)
Location: security/apparmor/label.c:2121
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
**Symbols:**

```
ffffffff814a3cc0-ffffffff814a40d7: __labelset_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __labelset_update(struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814946e0)
Location: security/apparmor/label.c:2121
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
**Symbols:**

```
ffffffff814946e0-ffffffff81494af7: __labelset_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __labelset_update(struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8149fd60)
Location: security/apparmor/label.c:2121
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
**Symbols:**

```
ffffffff8149fd60-ffffffff814a0177: __labelset_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __labelset_update(struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814b8390)
Location: security/apparmor/label.c:2121
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
**Symbols:**

```
ffffffff814b8390-ffffffff814b87fe: __labelset_update (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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

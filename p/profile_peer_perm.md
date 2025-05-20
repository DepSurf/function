# Function: <code>profile_peer_perm</code>

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
In security/apparmor/af_unix.c (ffffffff8139362d)
Location: security/apparmor/af_unix.c:491
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
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
In security/apparmor/af_unix.c (ffffffff813cede9)
Location: security/apparmor/af_unix.c:491
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
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
In security/apparmor/af_unix.c (ffffffff813e6469)
Location: security/apparmor/af_unix.c:491
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
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
In security/apparmor/af_unix.c (ffffffff813f2917)
Location: security/apparmor/af_unix.c:499
Inline: True
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
In security/apparmor/af_unix.c (ffffffff8141a997)
Location: security/apparmor/af_unix.c:499
Inline: True
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
In security/apparmor/af_unix.c (ffffffff8144da25)
Location: security/apparmor/af_unix.c:500
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
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
In security/apparmor/af_unix.c (ffffffff8146a9e8)
Location: security/apparmor/af_unix.c:500
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814979f8)
Location: security/apparmor/af_unix.c:500
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814b1928)
Location: security/apparmor/af_unix.c:500
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
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
In security/apparmor/af_unix.c (ffffffff8150fbe0)
Location: security/apparmor/af_unix.c:500
Inline: True
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff8150fbe0-ffffffff8150fec3: profile_peer_perm.constprop.0 (STB_LOCAL)
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
In security/apparmor/af_unix.c (ffffffff8152ca30)
Location: security/apparmor/af_unix.c:500
Inline: True
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff8152ca30-ffffffff8152cd13: profile_peer_perm.constprop.0 (STB_LOCAL)
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
In security/apparmor/af_unix.c (ffffffff81532d60)
Location: security/apparmor/af_unix.c:500
Inline: True
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff81532d60-ffffffff81533043: profile_peer_perm.constprop.0 (STB_LOCAL)
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
In security/apparmor/af_unix.c (ffffffff815912e0)
Location: security/apparmor/af_unix.c:500
Inline: True
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff815912e0-ffffffff815915c3: profile_peer_perm.constprop.0 (STB_LOCAL)
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
In security/apparmor/af_unix.c (ffffffff81632df0)
Location: security/apparmor/af_unix.c:523
Inline: True
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff81632df0-ffffffff816331b1: profile_peer_perm.constprop.0 (STB_LOCAL)
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
In security/apparmor/af_unix.c (ffffffff816e7c30)
Location: security/apparmor/af_unix.c:541
Inline: True
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff816e7c30-ffffffff816e7fd5: profile_peer_perm.constprop.0 (STB_LOCAL)
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
In security/apparmor/af_unix.c (ffffffff817213b0)
Location: security/apparmor/af_unix.c:541
Inline: True
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff817213b0-ffffffff8172175e: profile_peer_perm.isra.0 (STB_LOCAL)
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
In security/apparmor/af_unix.c (ffffffff8175fed0)
Location: security/apparmor/af_unix.c:541
Inline: True
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff8175fed0-ffffffff8176027e: profile_peer_perm.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffff8000105a9220)
Location: security/apparmor/af_unix.c:500
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (c0759328)
Location: security/apparmor/af_unix.c:500
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (c000000000726660)
Location: security/apparmor/af_unix.c:500
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffe0003f26b6)
Location: security/apparmor/af_unix.c:500
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814a9f08)
Location: security/apparmor/af_unix.c:500
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8149a928)
Location: security/apparmor/af_unix.c:500
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814a5fa8)
Location: security/apparmor/af_unix.c:500
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814be858)
Location: security/apparmor/af_unix.c:500
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
</details>
</li>
</ul>

## Differences

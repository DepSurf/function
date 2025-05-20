# Function: <code>change_hat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct aa_label *change_hat(struct aa_label *label, const char **hats, int count, bool permtest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8137a8a0)
Location: security/apparmor/domain.c:867
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_hat
```
**Symbols:**

```
ffffffff8137a8a0-ffffffff8137b404: change_hat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/domain.c (ffffffff813b38b0)
Location: security/apparmor/domain.c:894
Inline: True
Direct callers:
  - security/apparmor/domain.c:aa_change_hat
```
**Symbols:**

```
ffffffff813b38b0-ffffffff813b44b6: change_hat.constprop.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/domain.c (ffffffff813caac0)
Location: security/apparmor/domain.c:916
Inline: True
Direct callers:
  - security/apparmor/domain.c:aa_change_hat
```
**Symbols:**

```
ffffffff813caac0-ffffffff813cb6c6: change_hat.constprop.9 (STB_LOCAL)
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
In security/apparmor/domain.c (ffffffff813e0080)
Location: security/apparmor/domain.c:920
Inline: True
Direct callers:
  - security/apparmor/domain.c:aa_change_hat
```
**Symbols:**

```
ffffffff813e0080-ffffffff813e08c5: change_hat.isra.6 (STB_LOCAL)
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
In security/apparmor/domain.c (ffffffff81406a60)
Location: security/apparmor/domain.c:936
Inline: True
Direct callers:
  - security/apparmor/domain.c:aa_change_hat
```
**Symbols:**

```
ffffffff81406a60-ffffffff81407322: change_hat.isra.6 (STB_LOCAL)
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
In security/apparmor/domain.c (ffffffff81438190)
Location: security/apparmor/domain.c:1053
Inline: True
Direct callers:
  - security/apparmor/domain.c:aa_change_hat
```
**Symbols:**

```
ffffffff81438190-ffffffff81438a06: change_hat.isra.8 (STB_LOCAL)
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
In security/apparmor/domain.c (ffffffff81454e00)
Location: security/apparmor/domain.c:1053
Inline: True
Direct callers:
  - security/apparmor/domain.c:aa_change_hat
```
**Symbols:**

```
ffffffff81454e00-ffffffff81455671: change_hat.isra.9 (STB_LOCAL)
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
In security/apparmor/domain.c (ffffffff814827a0)
Location: security/apparmor/domain.c:1049
Inline: True
Direct callers:
  - security/apparmor/domain.c:aa_change_hat
```
**Symbols:**

```
ffffffff814827a0-ffffffff814830b8: change_hat.isra.0 (STB_LOCAL)
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
In security/apparmor/domain.c (ffffffff8149c6b0)
Location: security/apparmor/domain.c:1053
Inline: True
Direct callers:
  - security/apparmor/domain.c:aa_change_hat
```
**Symbols:**

```
ffffffff8149c6b0-ffffffff8149cfc8: change_hat.isra.0 (STB_LOCAL)
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
In security/apparmor/domain.c (ffffffff814f52c0)
Location: security/apparmor/domain.c:1033
Inline: True
Direct callers:
  - security/apparmor/domain.c:aa_change_hat
```
**Symbols:**

```
ffffffff814f52c0-ffffffff814f5e40: change_hat.constprop.0 (STB_LOCAL)
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
In security/apparmor/domain.c (ffffffff81512420)
Location: security/apparmor/domain.c:1033
Inline: True
Direct callers:
  - security/apparmor/domain.c:aa_change_hat
```
**Symbols:**

```
ffffffff81512420-ffffffff81512fa5: change_hat.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct aa_label *change_hat(struct aa_label *label, const char **hats, int count, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81518d40)
Location: security/apparmor/domain.c:1036
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_hat
```
**Symbols:**

```
ffffffff81518d40-ffffffff815198c6: change_hat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct aa_label *change_hat(struct aa_label *label, const char **hats, int count, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/domain.c (0)
Location: security/apparmor/domain.c:1036
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_hat
```
**Symbols:**

```
ffffffff81576d50-ffffffff815778e5: change_hat (STB_LOCAL)
ffffffff81cd634b-ffffffff81cd6360: change_hat.cold (STB_LOCAL)
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
In security/apparmor/domain.c (0)
Location: security/apparmor/domain.c:1039
Inline: True
Direct callers:
  - security/apparmor/domain.c:aa_change_hat
```
**Symbols:**

```
ffffffff81614c70-ffffffff81615883: change_hat.constprop.0 (STB_LOCAL)
ffffffff81e89179-ffffffff81e8919b: change_hat.constprop.0.cold (STB_LOCAL)
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
In security/apparmor/domain.c (ffffffff816c79b0)
Location: security/apparmor/domain.c:1059
Inline: True
Direct callers:
  - security/apparmor/domain.c:aa_change_hat
```
**Symbols:**

```
ffffffff816c79b0-ffffffff816c8647: change_hat.constprop.0 (STB_LOCAL)
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
In security/apparmor/domain.c (ffffffff81700790)
Location: security/apparmor/domain.c:1059
Inline: True
Direct callers:
  - security/apparmor/domain.c:aa_change_hat
```
**Symbols:**

```
ffffffff81700790-ffffffff81701373: change_hat.isra.0 (STB_LOCAL)
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
In security/apparmor/domain.c (ffffffff8173ddb0)
Location: security/apparmor/domain.c:1066
Inline: True
Direct callers:
  - security/apparmor/domain.c:aa_change_hat
```
**Symbols:**

```
ffffffff8173ddb0-ffffffff8173e990: change_hat.isra.0 (STB_LOCAL)
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
In security/apparmor/domain.c (ffff800010592808)
Location: security/apparmor/domain.c:1053
Inline: True
Direct callers:
  - security/apparmor/domain.c:aa_change_hat
```
**Symbols:**

```
ffff800010592808-ffff8000105930ac: change_hat.isra.0 (STB_LOCAL)
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
In security/apparmor/domain.c (c0743440)
Location: security/apparmor/domain.c:1053
Inline: True
Direct callers:
  - security/apparmor/domain.c:aa_change_hat
```
**Symbols:**

```
c0743440-c0743d90: change_hat.constprop.0 (STB_LOCAL)
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
In security/apparmor/domain.c (c000000000706da0)
Location: security/apparmor/domain.c:1053
Inline: True
Direct callers:
  - security/apparmor/domain.c:aa_change_hat
```
**Symbols:**

```
c000000000706da0-c000000000707928: change_hat.isra.0 (STB_LOCAL)
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
In security/apparmor/domain.c (ffffffe0003e0038)
Location: security/apparmor/domain.c:1053
Inline: True
Direct callers:
  - security/apparmor/domain.c:aa_change_hat
```
**Symbols:**

```
ffffffe0003e0038-ffffffe0003e06fe: change_hat.isra.0 (STB_LOCAL)
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
In security/apparmor/domain.c (ffffffff81494c90)
Location: security/apparmor/domain.c:1053
Inline: True
Direct callers:
  - security/apparmor/domain.c:aa_change_hat
```
**Symbols:**

```
ffffffff81494c90-ffffffff814955a8: change_hat.isra.0 (STB_LOCAL)
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
In security/apparmor/domain.c (ffffffff814856b0)
Location: security/apparmor/domain.c:1053
Inline: True
Direct callers:
  - security/apparmor/domain.c:aa_change_hat
```
**Symbols:**

```
ffffffff814856b0-ffffffff81485fc8: change_hat.isra.0 (STB_LOCAL)
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
In security/apparmor/domain.c (ffffffff81490d30)
Location: security/apparmor/domain.c:1053
Inline: True
Direct callers:
  - security/apparmor/domain.c:aa_change_hat
```
**Symbols:**

```
ffffffff81490d30-ffffffff81491648: change_hat.isra.0 (STB_LOCAL)
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
In security/apparmor/domain.c (ffffffff814a8cb0)
Location: security/apparmor/domain.c:1053
Inline: True
Direct callers:
  - security/apparmor/domain.c:aa_change_hat
```
**Symbols:**

```
ffffffff814a8cb0-ffffffff814a95ee: change_hat.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>

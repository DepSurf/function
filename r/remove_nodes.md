# Function: <code>remove_nodes</code>

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
In drivers/base/devres.c (ffffffff8154fd44)
Location: drivers/base/devres.c:408
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
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
In drivers/base/devres.c (ffffffff815a1b24)
Location: drivers/base/devres.c:408
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
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
In drivers/base/devres.c (ffffffff815d0244)
Location: drivers/base/devres.c:409
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
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
In drivers/base/devres.c (ffffffff815e4f84)
Location: drivers/base/devres.c:409
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
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
In drivers/base/devres.c (ffffffff8164c264)
Location: drivers/base/devres.c:409
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
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
In drivers/base/devres.c (ffffffff81687854)
Location: drivers/base/devres.c:413
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
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
In drivers/base/devres.c (ffffffff816a7274)
Location: drivers/base/devres.c:421
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
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
In drivers/base/devres.c (ffffffff816e0367)
Location: drivers/base/devres.c:421
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
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
In drivers/base/devres.c (ffffffff81704597)
Location: drivers/base/devres.c:421
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
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
In drivers/base/devres.c (ffffffff817be180)
Location: drivers/base/devres.c:421
Inline: True
Direct callers:
  - drivers/base/devres.c:release_nodes
```
**Symbols:**

```
ffffffff817be180-ffffffff817be2da: remove_nodes.constprop.0 (STB_LOCAL)
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
In drivers/base/devres.c (ffffffff817d2ed0)
Location: drivers/base/devres.c:437
Inline: True
Direct callers:
  - drivers/base/devres.c:release_nodes
```
**Symbols:**

```
ffffffff817d2ed0-ffffffff817d302a: remove_nodes.constprop.0 (STB_LOCAL)
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
In drivers/base/devres.c (ffffffff817b68e0)
Location: drivers/base/devres.c:437
Inline: True
Direct callers:
  - drivers/base/devres.c:release_nodes
```
**Symbols:**

```
ffffffff817b68e0-ffffffff817b6a3a: remove_nodes.constprop.0 (STB_LOCAL)
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
In drivers/base/devres.c (ffffffff8183fe90)
Location: drivers/base/devres.c:430
Inline: True
Direct callers:
  - drivers/base/devres.c:devres_release_group
  - drivers/base/devres.c:devres_release_all
```
**Symbols:**

```
ffffffff8183fe90-ffffffff81840002: remove_nodes.constprop.0 (STB_LOCAL)
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
In drivers/base/devres.c (ffffffff81983060)
Location: drivers/base/devres.c:430
Inline: True
Direct callers:
  - drivers/base/devres.c:devres_release_group
  - drivers/base/devres.c:devres_release_all
```
**Symbols:**

```
ffffffff81983060-ffffffff81983202: remove_nodes.constprop.0 (STB_LOCAL)
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
In drivers/base/devres.c (ffffffff81af1000)
Location: drivers/base/devres.c:435
Inline: True
Direct callers:
  - drivers/base/devres.c:devres_release_group
  - drivers/base/devres.c:devres_release_all
```
**Symbols:**

```
ffffffff81af1000-ffffffff81af11a2: remove_nodes.constprop.0 (STB_LOCAL)
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
In drivers/base/devres.c (ffffffff81b3f160)
Location: drivers/base/devres.c:435
Inline: True
Direct callers:
  - drivers/base/devres.c:devres_release_group
  - drivers/base/devres.c:devres_release_all
```
**Symbols:**

```
ffffffff81b3f160-ffffffff81b3f302: remove_nodes.isra.0 (STB_LOCAL)
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
In drivers/base/devres.c (ffffffff81b96fe0)
Location: drivers/base/devres.c:435
Inline: True
Direct callers:
  - drivers/base/devres.c:devres_release_group
  - drivers/base/devres.c:devres_release_all
```
**Symbols:**

```
ffffffff81b96fe0-ffffffff81b97182: remove_nodes.isra.0 (STB_LOCAL)
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
In drivers/base/devres.c (ffff8000108efff0)
Location: drivers/base/devres.c:421
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
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
In drivers/base/devres.c (c09dddd8)
Location: drivers/base/devres.c:421
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
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
In drivers/base/devres.c (c000000000989f0c)
Location: drivers/base/devres.c:421
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
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
In drivers/base/devres.c (ffffffe000582984)
Location: drivers/base/devres.c:421
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
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
In drivers/base/devres.c (ffffffff816c9ce7)
Location: drivers/base/devres.c:421
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
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
In drivers/base/devres.c (ffffffff816a5017)
Location: drivers/base/devres.c:421
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
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
In drivers/base/devres.c (ffffffff816f8257)
Location: drivers/base/devres.c:421
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
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
In drivers/base/devres.c (ffffffff81712af7)
Location: drivers/base/devres.c:421
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
```
</details>
</li>
</ul>

## Differences

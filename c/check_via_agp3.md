# Function: <code>check_via_agp3</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/agp/via-agp.c (ffffffff816f4af4)
Location: drivers/char/agp/via-agp.c:429
Inline: True
Direct callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
```
**Symbols:**

```
ffffffff816f4af4-ffffffff816f4b52: check_via_agp3.isra.5 (STB_LOCAL)
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
In drivers/char/agp/via-agp.c (ffffffff81759b60)
Location: drivers/char/agp/via-agp.c:429
Inline: True
Direct callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
```
**Symbols:**

```
ffffffff81759b60-ffffffff81759bbe: check_via_agp3.isra.5 (STB_LOCAL)
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
In drivers/char/agp/via-agp.c (ffffffff81786002)
Location: drivers/char/agp/via-agp.c:429
Inline: True
Direct callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
```
**Symbols:**

```
ffffffff81786002-ffffffff81786060: check_via_agp3.isra.5 (STB_LOCAL)
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
In drivers/char/agp/via-agp.c (ffffffff815b6665)
Location: drivers/char/agp/via-agp.c:429
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
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
In drivers/char/agp/via-agp.c (ffffffff8161d375)
Location: drivers/char/agp/via-agp.c:429
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
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
In drivers/char/agp/via-agp.c (ffffffff81657036)
Location: drivers/char/agp/via-agp.c:429
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
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
In drivers/char/agp/via-agp.c (ffffffff81675136)
Location: drivers/char/agp/via-agp.c:429
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
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
In drivers/char/agp/via-agp.c (ffffffff816aabda)
Location: drivers/char/agp/via-agp.c:430
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
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
In drivers/char/agp/via-agp.c (ffffffff816cd91a)
Location: drivers/char/agp/via-agp.c:430
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void check_via_agp3(struct agp_bridge_data *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/via-agp.c (ffffffff81782732)
Location: drivers/char/agp/via-agp.c:430
Inline: False
Direct callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
```
**Symbols:**

```
ffffffff81782732-ffffffff8178278b: check_via_agp3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void check_via_agp3(struct agp_bridge_data *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/via-agp.c (ffffffff81c0a14c)
Location: drivers/char/agp/via-agp.c:430
Inline: False
Direct callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
```
**Symbols:**

```
ffffffff81c0a14c-ffffffff81c0a1a5: check_via_agp3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void check_via_agp3(struct agp_bridge_data *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/via-agp.c (ffffffff81bfbbd3)
Location: drivers/char/agp/via-agp.c:430
Inline: False
Direct callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
```
**Symbols:**

```
ffffffff81bfbbd3-ffffffff81bfbc2c: check_via_agp3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void check_via_agp3(struct agp_bridge_data *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/via-agp.c (ffffffff81cfc857)
Location: drivers/char/agp/via-agp.c:430
Inline: False
Direct callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
```
**Symbols:**

```
ffffffff81cfc857-ffffffff81cfc8b0: check_via_agp3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void check_via_agp3(struct agp_bridge_data *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/via-agp.c (ffffffff81ec5082)
Location: drivers/char/agp/via-agp.c:427
Inline: False
Direct callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
```
**Symbols:**

```
ffffffff81ec5082-ffffffff81ec50eb: check_via_agp3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/via-agp.c (ffffffff81aa4a83)
Location: drivers/char/agp/via-agp.c:427
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/via-agp.c (ffffffff81af03a3)
Location: drivers/char/agp/via-agp.c:427
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/via-agp.c (ffffffff81b438e3)
Location: drivers/char/agp/via-agp.c:427
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In drivers/char/agp/via-agp.c (ffffffff8169336a)
Location: drivers/char/agp/via-agp.c:430
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
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
In drivers/char/agp/via-agp.c (ffffffff81670d5a)
Location: drivers/char/agp/via-agp.c:430
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
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
In drivers/char/agp/via-agp.c (ffffffff816c15da)
Location: drivers/char/agp/via-agp.c:430
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
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
In drivers/char/agp/via-agp.c (ffffffff816dbbaa)
Location: drivers/char/agp/via-agp.c:430
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>

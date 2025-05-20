# Function: <code>da9052_clear_fault_log</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9052-core.c (ffffffff8160f229)
Location: drivers/mfd/da9052-core.c:545
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
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
In drivers/mfd/da9052-core.c (ffffffff81623327)
Location: drivers/mfd/da9052-core.c:545
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
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
In drivers/mfd/da9052-core.c (ffffffff8168bb97)
Location: drivers/mfd/da9052-core.c:549
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
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
In drivers/mfd/da9052-core.c (ffffffff816c7c59)
Location: drivers/mfd/da9052-core.c:549
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
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
In drivers/mfd/da9052-core.c (ffffffff816e9119)
Location: drivers/mfd/da9052-core.c:549
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int da9052_clear_fault_log(struct da9052 *da9052);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/da9052-core.c (0)
Location: drivers/mfd/da9052-core.c:545
Inline: False
Direct callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
**Symbols:**

```
ffffffff81722770-ffffffff81722997: da9052_clear_fault_log (STB_LOCAL)
ffffffff81722afc-ffffffff81722b2a: da9052_clear_fault_log.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int da9052_clear_fault_log(struct da9052 *da9052);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/da9052-core.c (0)
Location: drivers/mfd/da9052-core.c:545
Inline: False
Direct callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
**Symbols:**

```
ffffffff81746a10-ffffffff81746c37: da9052_clear_fault_log (STB_LOCAL)
ffffffff81746d9c-ffffffff81746dca: da9052_clear_fault_log.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int da9052_clear_fault_log(struct da9052 *da9052);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/da9052-core.c (0)
Location: drivers/mfd/da9052-core.c:545
Inline: False
Direct callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
**Symbols:**

```
ffffffff81804710-ffffffff81804937: da9052_clear_fault_log (STB_LOCAL)
ffffffff81804a9e-ffffffff81804acc: da9052_clear_fault_log.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int da9052_clear_fault_log(struct da9052 *da9052);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/da9052-core.c (0)
Location: drivers/mfd/da9052-core.c:545
Inline: False
Direct callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
**Symbols:**

```
ffffffff81815140-ffffffff81815367: da9052_clear_fault_log (STB_LOCAL)
ffffffff81c13a38-ffffffff81c13a66: da9052_clear_fault_log.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int da9052_clear_fault_log(struct da9052 *da9052);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/da9052-core.c (0)
Location: drivers/mfd/da9052-core.c:545
Inline: False
Direct callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
**Symbols:**

```
ffffffff817f9820-ffffffff817f9a47: da9052_clear_fault_log (STB_LOCAL)
ffffffff81c05bb0-ffffffff81c05bde: da9052_clear_fault_log.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int da9052_clear_fault_log(struct da9052 *da9052);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/da9052-core.c (0)
Location: drivers/mfd/da9052-core.c:545
Inline: False
Direct callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
**Symbols:**

```
ffffffff81882cd0-ffffffff81882ef7: da9052_clear_fault_log (STB_LOCAL)
ffffffff81d09072-ffffffff81d090a0: da9052_clear_fault_log.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int da9052_clear_fault_log(struct da9052 *da9052);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/da9052-core.c (0)
Location: drivers/mfd/da9052-core.c:545
Inline: False
Direct callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
**Symbols:**

```
ffffffff819cb6a0-ffffffff819cb8c9: da9052_clear_fault_log (STB_LOCAL)
ffffffff81ed14b4-ffffffff81ed14e2: da9052_clear_fault_log.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int da9052_clear_fault_log(struct da9052 *da9052);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9052-core.c (ffffffff81b43050)
Location: drivers/mfd/da9052-core.c:545
Inline: False
Direct callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
**Symbols:**

```
ffffffff81b43050-ffffffff81b4326b: da9052_clear_fault_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int da9052_clear_fault_log(struct da9052 *da9052);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9052-core.c (ffffffff81b963c0)
Location: drivers/mfd/da9052-core.c:545
Inline: False
Direct callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
**Symbols:**

```
ffffffff81b963c0-ffffffff81b965db: da9052_clear_fault_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int da9052_clear_fault_log(struct da9052 *da9052);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9052-core.c (ffffffff81bea390)
Location: drivers/mfd/da9052-core.c:545
Inline: False
Direct callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
**Symbols:**

```
ffffffff81bea390-ffffffff81bea5ab: da9052_clear_fault_log (STB_LOCAL)
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
int da9052_clear_fault_log(struct da9052 *da9052);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9052-core.c (ffff800010943458)
Location: drivers/mfd/da9052-core.c:545
Inline: False
Direct callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
**Symbols:**

```
ffff800010943458-ffff800010943698: da9052_clear_fault_log (STB_LOCAL)
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
In drivers/mfd/da9052-core.c (c0a2c684)
Location: drivers/mfd/da9052-core.c:545
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
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
In drivers/mfd/da9052-core.c (c0000000009eca8c)
Location: drivers/mfd/da9052-core.c:545
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
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
In drivers/mfd/da9052-core.c (ffffffe0005b621c)
Location: drivers/mfd/da9052-core.c:545
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
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
int da9052_clear_fault_log(struct da9052 *da9052);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/da9052-core.c (0)
Location: drivers/mfd/da9052-core.c:545
Inline: False
Direct callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
**Symbols:**

```
ffffffff81703a80-ffffffff81703ca7: da9052_clear_fault_log (STB_LOCAL)
ffffffff81703e0c-ffffffff81703e3a: da9052_clear_fault_log.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int da9052_clear_fault_log(struct da9052 *da9052);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/da9052-core.c (0)
Location: drivers/mfd/da9052-core.c:545
Inline: False
Direct callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
**Symbols:**

```
ffffffff816d7880-ffffffff816d7aa7: da9052_clear_fault_log (STB_LOCAL)
ffffffff816d7c0c-ffffffff816d7c3a: da9052_clear_fault_log.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int da9052_clear_fault_log(struct da9052 *da9052);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/da9052-core.c (0)
Location: drivers/mfd/da9052-core.c:545
Inline: False
Direct callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
**Symbols:**

```
ffffffff81739ed0-ffffffff8173a0f7: da9052_clear_fault_log (STB_LOCAL)
ffffffff8173a25c-ffffffff8173a28a: da9052_clear_fault_log.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int da9052_clear_fault_log(struct da9052 *da9052);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/da9052-core.c (0)
Location: drivers/mfd/da9052-core.c:545
Inline: False
Direct callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
**Symbols:**

```
ffffffff81755310-ffffffff81755537: da9052_clear_fault_log (STB_LOCAL)
ffffffff8175569c-ffffffff817556ca: da9052_clear_fault_log.cold (STB_LOCAL)
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

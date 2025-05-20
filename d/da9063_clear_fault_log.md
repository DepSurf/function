# Function: <code>da9063_clear_fault_log</code>

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
In drivers/mfd/da9063-core.c (ffffffff8158e221)
Location: drivers/mfd/da9063-core.c:114
Inline: True
Inline callers:
  - drivers/mfd/da9063-core.c:da9063_device_init
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
In drivers/mfd/da9063-core.c (ffffffff815e3101)
Location: drivers/mfd/da9063-core.c:114
Inline: True
Inline callers:
  - drivers/mfd/da9063-core.c:da9063_device_init
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
In drivers/mfd/da9063-core.c (ffffffff8160ffb1)
Location: drivers/mfd/da9063-core.c:114
Inline: True
Inline callers:
  - drivers/mfd/da9063-core.c:da9063_device_init
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
In drivers/mfd/da9063-core.c (ffffffff81624061)
Location: drivers/mfd/da9063-core.c:114
Inline: True
Inline callers:
  - drivers/mfd/da9063-core.c:da9063_device_init
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
In drivers/mfd/da9063-core.c (ffffffff8168c951)
Location: drivers/mfd/da9063-core.c:114
Inline: True
Inline callers:
  - drivers/mfd/da9063-core.c:da9063_device_init
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
In drivers/mfd/da9063-core.c (ffffffff816c8a5e)
Location: drivers/mfd/da9063-core.c:114
Inline: True
Inline callers:
  - drivers/mfd/da9063-core.c:da9063_device_init
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
In drivers/mfd/da9063-core.c (ffffffff816e9fbe)
Location: drivers/mfd/da9063-core.c:118
Inline: True
Inline callers:
  - drivers/mfd/da9063-core.c:da9063_device_init
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
In drivers/mfd/da9063-core.c (ffffffff81723752)
Location: drivers/mfd/da9063-core.c:113
Inline: True
Inline callers:
  - drivers/mfd/da9063-core.c:da9063_device_init
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
In drivers/mfd/da9063-core.c (ffffffff817479f2)
Location: drivers/mfd/da9063-core.c:113
Inline: True
Inline callers:
  - drivers/mfd/da9063-core.c:da9063_device_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int da9063_clear_fault_log(struct da9063 *da9063);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/da9063-core.c (0)
Location: drivers/mfd/da9063-core.c:113
Inline: False
Direct callers:
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffffffff818056c0-ffffffff818058bd: da9063_clear_fault_log (STB_LOCAL)
ffffffff81805949-ffffffff8180597e: da9063_clear_fault_log.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int da9063_clear_fault_log(struct da9063 *da9063);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/da9063-core.c (0)
Location: drivers/mfd/da9063-core.c:113
Inline: False
Direct callers:
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffffffff81815f60-ffffffff8181615d: da9063_clear_fault_log (STB_LOCAL)
ffffffff81c13bbf-ffffffff81c13bf4: da9063_clear_fault_log.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int da9063_clear_fault_log(struct da9063 *da9063);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/da9063-core.c (0)
Location: drivers/mfd/da9063-core.c:113
Inline: False
Direct callers:
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffffffff817fa610-ffffffff817fa80d: da9063_clear_fault_log (STB_LOCAL)
ffffffff81c05d43-ffffffff81c05d78: da9063_clear_fault_log.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int da9063_clear_fault_log(struct da9063 *da9063);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/da9063-core.c (0)
Location: drivers/mfd/da9063-core.c:113
Inline: False
Direct callers:
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffffffff81883b00-ffffffff81883cfa: da9063_clear_fault_log (STB_LOCAL)
ffffffff81d09205-ffffffff81d0923a: da9063_clear_fault_log.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int da9063_clear_fault_log(struct da9063 *da9063);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/da9063-core.c (0)
Location: drivers/mfd/da9063-core.c:113
Inline: False
Direct callers:
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffffffff819cc660-ffffffff819cc867: da9063_clear_fault_log (STB_LOCAL)
ffffffff81ed1640-ffffffff81ed1675: da9063_clear_fault_log.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int da9063_clear_fault_log(struct da9063 *da9063);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9063-core.c (ffffffff81b44510)
Location: drivers/mfd/da9063-core.c:113
Inline: False
Direct callers:
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffffffff81b44510-ffffffff81b446fa: da9063_clear_fault_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int da9063_clear_fault_log(struct da9063 *da9063);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9063-core.c (ffffffff81b978e0)
Location: drivers/mfd/da9063-core.c:113
Inline: False
Direct callers:
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffffffff81b978e0-ffffffff81b97aca: da9063_clear_fault_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int da9063_clear_fault_log(struct da9063 *da9063);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9063-core.c (ffffffff81beb8b0)
Location: drivers/mfd/da9063-core.c:113
Inline: False
Direct callers:
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffffffff81beb8b0-ffffffff81beba9a: da9063_clear_fault_log (STB_LOCAL)
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
In drivers/mfd/da9063-core.c (ffff80001094463c)
Location: drivers/mfd/da9063-core.c:113
Inline: True
Inline callers:
  - drivers/mfd/da9063-core.c:da9063_device_init
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
In drivers/mfd/da9063-core.c (c0a2d834)
Location: drivers/mfd/da9063-core.c:113
Inline: True
Inline callers:
  - drivers/mfd/da9063-core.c:da9063_device_init
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
In drivers/mfd/da9063-core.c (c0000000009ee288)
Location: drivers/mfd/da9063-core.c:113
Inline: True
Inline callers:
  - drivers/mfd/da9063-core.c:da9063_device_init
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
In drivers/mfd/da9063-core.c (ffffffe0005b706a)
Location: drivers/mfd/da9063-core.c:113
Inline: True
Inline callers:
  - drivers/mfd/da9063-core.c:da9063_device_init
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9063-core.c (ffffffff8173aeb2)
Location: drivers/mfd/da9063-core.c:113
Inline: True
Inline callers:
  - drivers/mfd/da9063-core.c:da9063_device_init
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
In drivers/mfd/da9063-core.c (ffffffff817562f2)
Location: drivers/mfd/da9063-core.c:113
Inline: True
Inline callers:
  - drivers/mfd/da9063-core.c:da9063_device_init
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

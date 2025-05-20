# Function: <code>__default_power_down_ok</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain_governor.c (ffffffff815b1035)
Location: drivers/base/power/domain_governor.c:101
Inline: True
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
In drivers/base/power/domain_governor.c (ffffffff815e0305)
Location: drivers/base/power/domain_governor.c:101
Inline: True
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
In drivers/base/power/domain_governor.c (ffffffff815f51dd)
Location: drivers/base/power/domain_governor.c:95
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
In drivers/base/power/domain_governor.c (ffffffff8165d116)
Location: drivers/base/power/domain_governor.c:119
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
In drivers/base/power/domain_governor.c (ffffffff81698e49)
Location: drivers/base/power/domain_governor.c:119
Inline: True
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
In drivers/base/power/domain_governor.c (ffffffff816b96b2)
Location: drivers/base/power/domain_governor.c:119
Inline: True
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
In drivers/base/power/domain_governor.c (ffffffff816f381c)
Location: drivers/base/power/domain_governor.c:120
Inline: True
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
In drivers/base/power/domain_governor.c (ffffffff81717c1c)
Location: drivers/base/power/domain_governor.c:120
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __default_power_down_ok(struct dev_pm_domain *pd, unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain_governor.c (ffffffff817d35b0)
Location: drivers/base/power/domain_governor.c:120
Inline: False
```
**Symbols:**

```
ffffffff817d35b0-ffffffff817d36b8: __default_power_down_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __default_power_down_ok(struct dev_pm_domain *pd, unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain_governor.c (ffffffff817e8010)
Location: drivers/base/power/domain_governor.c:120
Inline: False
```
**Symbols:**

```
ffffffff817e8010-ffffffff817e8117: __default_power_down_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain_governor.c (ffffffff817cc5b5)
Location: drivers/base/power/domain_governor.c:169
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:_default_power_down_ok
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain_governor.c (ffffffff81856ce4)
Location: drivers/base/power/domain_governor.c:169
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:_default_power_down_ok
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain_governor.c (ffffffff8199d12f)
Location: drivers/base/power/domain_governor.c:174
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:_default_power_down_ok
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
In drivers/base/power/domain_governor.c (ffffffff81b0e7bf)
Location: drivers/base/power/domain_governor.c:174
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:_default_power_down_ok
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
In drivers/base/power/domain_governor.c (ffffffff81b5c86f)
Location: drivers/base/power/domain_governor.c:174
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:_default_power_down_ok
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
In drivers/pmdomain/governor.c (ffffffff81aa436f)
Location: drivers/pmdomain/governor.c:176
Inline: True
Inline callers:
  - drivers/pmdomain/governor.c:_default_power_down_ok
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
In drivers/base/power/domain_governor.c (ffff80001090aa44)
Location: drivers/base/power/domain_governor.c:120
Inline: True
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
In drivers/base/power/domain_governor.c (c09f4234)
Location: drivers/base/power/domain_governor.c:120
Inline: True
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
In drivers/base/power/domain_governor.c (c0000000009ab0a0)
Location: drivers/base/power/domain_governor.c:120
Inline: True
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
In drivers/base/power/domain_governor.c (ffffffe0005907e6)
Location: drivers/base/power/domain_governor.c:120
Inline: True
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
In drivers/base/power/domain_governor.c (ffffffff816ddf4c)
Location: drivers/base/power/domain_governor.c:120
Inline: True
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
In drivers/base/power/domain_governor.c (ffffffff816b85ac)
Location: drivers/base/power/domain_governor.c:120
Inline: True
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
In drivers/base/power/domain_governor.c (ffffffff8170b8dc)
Location: drivers/base/power/domain_governor.c:120
Inline: True
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
In drivers/base/power/domain_governor.c (ffffffff817262cc)
Location: drivers/base/power/domain_governor.c:120
Inline: True
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
</ul>

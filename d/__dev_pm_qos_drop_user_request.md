# Function: <code>__dev_pm_qos_drop_user_request</code>

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
In drivers/base/power/qos.c (ffffffff81555001)
Location: drivers/base/power/qos.c:606
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
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
In drivers/base/power/qos.c (ffffffff815a7cf4)
Location: drivers/base/power/qos.c:606
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
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
In drivers/base/power/qos.c (ffffffff815d606c)
Location: drivers/base/power/qos.c:606
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
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
In drivers/base/power/qos.c (ffffffff815eaa8c)
Location: drivers/base/power/qos.c:563
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
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
In drivers/base/power/qos.c (ffffffff81651e3c)
Location: drivers/base/power/qos.c:566
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
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
In drivers/base/power/qos.c (ffffffff8168d71c)
Location: drivers/base/power/qos.c:566
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
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
In drivers/base/power/qos.c (ffffffff816ad96c)
Location: drivers/base/power/qos.c:566
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
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
In drivers/base/power/qos.c (ffffffff816e7792)
Location: drivers/base/power/qos.c:664
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:__dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
```
**Symbols:**

```
ffffffff816e7d29-ffffffff816e7d42: __dev_pm_qos_drop_user_request.isra.0.part.0 (STB_LOCAL)
ffffffff816e6ca0-ffffffff816e6d15: __dev_pm_qos_drop_user_request.isra.0 (STB_LOCAL)
ffffffff816e7d42-ffffffff816e7d4c: __dev_pm_qos_drop_user_request.isra.0.cold (STB_LOCAL)
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
In drivers/base/power/qos.c (ffffffff8170aff0)
Location: drivers/base/power/qos.c:598
Inline: True
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:__dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
```
**Symbols:**

```
ffffffff8170aff0-ffffffff8170b055: __dev_pm_qos_drop_user_request.isra.0 (STB_LOCAL)
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
In drivers/base/power/qos.c (ffffffff817c66af)
Location: drivers/base/power/qos.c:659
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
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
In drivers/base/power/qos.c (ffffffff817db12f)
Location: drivers/base/power/qos.c:659
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
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
In drivers/base/power/qos.c (ffffffff817bf47f)
Location: drivers/base/power/qos.c:659
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
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
In drivers/base/power/qos.c (ffffffff818497ef)
Location: drivers/base/power/qos.c:659
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
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
In drivers/base/power/qos.c (ffffffff8198e7c1)
Location: drivers/base/power/qos.c:659
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
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
In drivers/base/power/qos.c (ffffffff81afe7d1)
Location: drivers/base/power/qos.c:659
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
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
In drivers/base/power/qos.c (ffffffff81b4cb91)
Location: drivers/base/power/qos.c:659
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
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
In drivers/base/power/qos.c (ffffffff81ba5061)
Location: drivers/base/power/qos.c:659
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
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
In drivers/base/power/qos.c (ffff8000108f9a50)
Location: drivers/base/power/qos.c:598
Inline: True
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:__dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
```
**Symbols:**

```
ffff8000108f9a50-ffff8000108f9aec: __dev_pm_qos_drop_user_request.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __dev_pm_qos_drop_user_request(struct device *dev, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (c09e5614)
Location: drivers/base/power/qos.c:598
Inline: True
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:__dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
```
**Symbols:**

```
c09e5614-c09e567c: __dev_pm_qos_drop_user_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __dev_pm_qos_drop_user_request(struct device *dev, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (c000000000995f40)
Location: drivers/base/power/qos.c:598
Inline: True
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:__dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
```
**Symbols:**

```
c000000000995f40-c000000000995ffc: __dev_pm_qos_drop_user_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __dev_pm_qos_drop_user_request(struct device *dev, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffe000589330)
Location: drivers/base/power/qos.c:598
Inline: True
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:__dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
```
**Symbols:**

```
ffffffe000589330-ffffffe000589390: __dev_pm_qos_drop_user_request (STB_LOCAL)
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
In drivers/base/power/qos.c (ffffffff816d0740)
Location: drivers/base/power/qos.c:598
Inline: True
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:__dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
```
**Symbols:**

```
ffffffff816d0740-ffffffff816d07a5: __dev_pm_qos_drop_user_request.isra.0 (STB_LOCAL)
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
In drivers/base/power/qos.c (ffffffff816aba60)
Location: drivers/base/power/qos.c:598
Inline: True
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:__dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
```
**Symbols:**

```
ffffffff816aba60-ffffffff816abac5: __dev_pm_qos_drop_user_request.isra.0 (STB_LOCAL)
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
In drivers/base/power/qos.c (ffffffff816fecb0)
Location: drivers/base/power/qos.c:598
Inline: True
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:__dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
```
**Symbols:**

```
ffffffff816fecb0-ffffffff816fed15: __dev_pm_qos_drop_user_request.isra.0 (STB_LOCAL)
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
In drivers/base/power/qos.c (ffffffff81719920)
Location: drivers/base/power/qos.c:598
Inline: True
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:__dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
```
**Symbols:**

```
ffffffff81719920-ffffffff81719985: __dev_pm_qos_drop_user_request.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>

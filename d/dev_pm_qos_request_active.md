# Function: <code>dev_pm_qos_request_active</code>

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
In drivers/base/power/qos.c (0)
Location: include/linux/pm_qos.h:113
Inline: True
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
In drivers/base/power/qos.c (0)
Location: include/linux/pm_qos.h:113
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
In drivers/base/power/qos.c (0)
Location: include/linux/pm_qos.h:113
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
In drivers/base/power/qos.c (0)
Location: include/linux/pm_qos.h:112
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
In drivers/base/power/qos.c (0)
Location: include/linux/pm_qos.h:115
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
In drivers/base/power/qos.c (0)
Location: include/linux/pm_qos.h:115
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
In drivers/base/power/qos.c (0)
Location: include/linux/pm_qos.h:115
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
In drivers/base/power/qos.c (0)
Location: include/linux/pm_qos.h:123
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
In drivers/base/power/qos.c (0)
Location: include/linux/pm_qos.h:109
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff817c5ef0)
Location: include/linux/pm_qos.h:134
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/devfreq/devfreq.c (ffffffff819ce9d2)
Location: include/linux/pm_qos.h:134
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:devfreq_dev_release
  - drivers/devfreq/devfreq.c:devfreq_dev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff817da9ba)
Location: include/linux/pm_qos.h:134
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/devfreq/devfreq.c (ffffffff819ce522)
Location: include/linux/pm_qos.h:134
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:devfreq_dev_release
  - drivers/devfreq/devfreq.c:devfreq_dev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff817bed6a)
Location: include/linux/pm_qos.h:134
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/devfreq/devfreq.c (ffffffff819b3682)
Location: include/linux/pm_qos.h:134
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:devfreq_dev_release
  - drivers/devfreq/devfreq.c:devfreq_dev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff818490da)
Location: include/linux/pm_qos.h:134
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/devfreq/devfreq.c (ffffffff81a62032)
Location: include/linux/pm_qos.h:134
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:devfreq_dev_release
  - drivers/devfreq/devfreq.c:devfreq_dev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff8198e26a)
Location: include/linux/pm_qos.h:134
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/devfreq/devfreq.c (ffffffff81bd3002)
Location: include/linux/pm_qos.h:134
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:devfreq_dev_release
  - drivers/devfreq/devfreq.c:devfreq_dev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff81afe47a)
Location: include/linux/pm_qos.h:134
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/devfreq/devfreq.c (ffffffff81d7ee82)
Location: include/linux/pm_qos.h:134
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:devfreq_dev_release
  - drivers/devfreq/devfreq.c:devfreq_dev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff81b4c83a)
Location: include/linux/pm_qos.h:134
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/devfreq/devfreq.c (ffffffff81ded212)
Location: include/linux/pm_qos.h:134
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:devfreq_dev_release
  - drivers/devfreq/devfreq.c:devfreq_dev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff81ba4d0a)
Location: include/linux/pm_qos.h:134
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea35b2)
Location: include/linux/pm_qos.h:134
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:devfreq_dev_release
  - drivers/devfreq/devfreq.c:devfreq_dev_release
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
In drivers/base/power/qos.c (0)
Location: include/linux/pm_qos.h:109
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
In drivers/base/power/qos.c (c09e54dc)
Location: include/linux/pm_qos.h:109
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
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
In drivers/base/power/qos.c (0)
Location: include/linux/pm_qos.h:109
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
In drivers/base/power/qos.c (0)
Location: include/linux/pm_qos.h:109
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
In drivers/base/power/qos.c (0)
Location: include/linux/pm_qos.h:109
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
In drivers/base/power/qos.c (0)
Location: include/linux/pm_qos.h:109
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
In drivers/base/power/qos.c (0)
Location: include/linux/pm_qos.h:109
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
In drivers/base/power/qos.c (0)
Location: include/linux/pm_qos.h:109
Inline: True
```
</details>
</li>
</ul>

## Differences

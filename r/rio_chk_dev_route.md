# Function: <code>rio_chk_dev_route</code>

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
In drivers/rapidio/rio.c (ffffffff8145a861)
Location: drivers/rapidio/rio.c:665
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
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
In drivers/rapidio/rio.c (ffffffff814a89ce)
Location: drivers/rapidio/rio.c:966
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
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
In drivers/rapidio/rio.c (ffffffff814caade)
Location: drivers/rapidio/rio.c:966
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
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
In drivers/rapidio/rio.c (ffffffff814d6867)
Location: drivers/rapidio/rio.c:963
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
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
In drivers/rapidio/rio.c (ffffffff81516d52)
Location: drivers/rapidio/rio.c:963
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
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
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:958
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
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
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:958
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
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
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:954
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
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
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:954
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rio_chk_dev_route(struct rio_dev *rdev, struct rio_dev **nrdev, int *npnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff8165d960)
Location: drivers/rapidio/rio.c:954
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff8165d960-ffffffff8165daa4: rio_chk_dev_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rio_chk_dev_route(struct rio_dev *rdev, struct rio_dev **nrdev, int *npnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff8167f080)
Location: drivers/rapidio/rio.c:954
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff8167f080-ffffffff8167f1c4: rio_chk_dev_route (STB_LOCAL)
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
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:954
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
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
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:954
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
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
In drivers/rapidio/rio.c (ffffffff817ff975)
Location: drivers/rapidio/rio.c:954
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
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
In drivers/rapidio/rio.c (ffffffff8192cac4)
Location: drivers/rapidio/rio.c:954
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
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
In drivers/rapidio/rio.c (ffffffff81970d58)
Location: drivers/rapidio/rio.c:954
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
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
In drivers/rapidio/rio.c (ffffffff819badc8)
Location: drivers/rapidio/rio.c:954
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
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
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:954
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
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
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:954
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
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
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:954
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
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
In drivers/rapidio/rio.c (ffffffe0004ec61c)
Location: drivers/rapidio/rio.c:954
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
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
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:954
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
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
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:954
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
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
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:954
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
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
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:954
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
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

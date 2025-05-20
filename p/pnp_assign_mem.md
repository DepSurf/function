# Function: <code>pnp_assign_mem</code>

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
In drivers/pnp/manager.c (ffffffff814b9831)
Location: drivers/pnp/manager.c:80
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
In drivers/pnp/manager.c (ffffffff815092ed)
Location: drivers/pnp/manager.c:80
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
In drivers/pnp/manager.c (ffffffff8152d50d)
Location: drivers/pnp/manager.c:80
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
In drivers/pnp/manager.c (ffffffff8154055d)
Location: drivers/pnp/manager.c:80
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
In drivers/pnp/manager.c (ffffffff815a367d)
Location: drivers/pnp/manager.c:81
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
In drivers/pnp/manager.c (ffffffff815db462)
Location: drivers/pnp/manager.c:81
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
In drivers/pnp/manager.c (ffffffff815f4c12)
Location: drivers/pnp/manager.c:81
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
In drivers/pnp/manager.c (ffffffff8162691a)
Location: drivers/pnp/manager.c:81
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
In drivers/pnp/manager.c (ffffffff8164840a)
Location: drivers/pnp/manager.c:81
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pnp_assign_mem(struct pnp_dev *dev, struct pnp_mem *rule, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/manager.c (ffffffff816f75e0)
Location: drivers/pnp/manager.c:81
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
```
**Symbols:**

```
ffffffff816f75e0-ffffffff816f7715: pnp_assign_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pnp_assign_mem(struct pnp_dev *dev, struct pnp_mem *rule, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/manager.c (ffffffff817143a0)
Location: drivers/pnp/manager.c:81
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
```
**Symbols:**

```
ffffffff817143a0-ffffffff817144d5: pnp_assign_mem (STB_LOCAL)
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
In drivers/pnp/manager.c (ffffffff816f569f)
Location: drivers/pnp/manager.c:81
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
In drivers/pnp/manager.c (ffffffff8176fcc4)
Location: drivers/pnp/manager.c:81
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
In drivers/pnp/manager.c (ffffffff818a50f3)
Location: drivers/pnp/manager.c:81
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
In drivers/pnp/manager.c (ffffffff819eef13)
Location: drivers/pnp/manager.c:81
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
In drivers/pnp/manager.c (ffffffff81a376ef)
Location: drivers/pnp/manager.c:81
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
In drivers/pnp/manager.c (ffffffff81a82eaf)
Location: drivers/pnp/manager.c:81
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
In drivers/pnp/manager.c (ffff8000107b58c4)
Location: drivers/pnp/manager.c:81
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
```
</details>
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
In drivers/pnp/manager.c (ffffffff8160e46a)
Location: drivers/pnp/manager.c:81
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
In drivers/pnp/manager.c (ffffffff816029ba)
Location: drivers/pnp/manager.c:81
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
In drivers/pnp/manager.c (ffffffff8163c24a)
Location: drivers/pnp/manager.c:81
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
In drivers/pnp/manager.c (ffffffff8165659a)
Location: drivers/pnp/manager.c:81
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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

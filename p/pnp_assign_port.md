# Function: <code>pnp_assign_port</code>

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
In drivers/pnp/manager.c (ffffffff814b97fa)
Location: drivers/pnp/manager.c:37
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
In drivers/pnp/manager.c (ffffffff815092b8)
Location: drivers/pnp/manager.c:37
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
In drivers/pnp/manager.c (ffffffff8152d4d8)
Location: drivers/pnp/manager.c:37
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
In drivers/pnp/manager.c (ffffffff81540507)
Location: drivers/pnp/manager.c:37
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
In drivers/pnp/manager.c (ffffffff815a3627)
Location: drivers/pnp/manager.c:38
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
In drivers/pnp/manager.c (ffffffff815db3ee)
Location: drivers/pnp/manager.c:38
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
In drivers/pnp/manager.c (ffffffff815f4b9e)
Location: drivers/pnp/manager.c:38
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
In drivers/pnp/manager.c (ffffffff81626994)
Location: drivers/pnp/manager.c:38
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
In drivers/pnp/manager.c (ffffffff81648484)
Location: drivers/pnp/manager.c:38
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
int pnp_assign_port(struct pnp_dev *dev, struct pnp_port *rule, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/manager.c (ffffffff816f74d0)
Location: drivers/pnp/manager.c:38
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
```
**Symbols:**

```
ffffffff816f74d0-ffffffff816f75d9: pnp_assign_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pnp_assign_port(struct pnp_dev *dev, struct pnp_port *rule, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/manager.c (ffffffff81714290)
Location: drivers/pnp/manager.c:38
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
```
**Symbols:**

```
ffffffff81714290-ffffffff81714399: pnp_assign_port (STB_LOCAL)
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
In drivers/pnp/manager.c (ffffffff816f570f)
Location: drivers/pnp/manager.c:38
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
In drivers/pnp/manager.c (ffffffff8176fd30)
Location: drivers/pnp/manager.c:38
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
In drivers/pnp/manager.c (ffffffff818a516c)
Location: drivers/pnp/manager.c:38
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
In drivers/pnp/manager.c (ffffffff819eef8c)
Location: drivers/pnp/manager.c:38
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
In drivers/pnp/manager.c (ffffffff81a37871)
Location: drivers/pnp/manager.c:38
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
In drivers/pnp/manager.c (ffffffff81a83031)
Location: drivers/pnp/manager.c:38
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
In drivers/pnp/manager.c (ffff8000107b5758)
Location: drivers/pnp/manager.c:38
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
In drivers/pnp/manager.c (ffffffff8160e4e4)
Location: drivers/pnp/manager.c:38
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
In drivers/pnp/manager.c (ffffffff81602a34)
Location: drivers/pnp/manager.c:38
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
In drivers/pnp/manager.c (ffffffff8163c2c4)
Location: drivers/pnp/manager.c:38
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
In drivers/pnp/manager.c (ffffffff81656614)
Location: drivers/pnp/manager.c:38
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

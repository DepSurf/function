# Function: <code>netdev_boot_setup_add</code>

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
In net/core/dev.c (ffffffff81fbaf6f)
Location: net/core/dev.c:555
Inline: True
Inline callers:
  - net/core/dev.c:netdev_boot_setup
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
In net/core/dev.c (ffffffff81fe8b4a)
Location: net/core/dev.c:559
Inline: True
Inline callers:
  - net/core/dev.c:netdev_boot_setup
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
In net/core/dev.c (ffffffff82027370)
Location: net/core/dev.c:558
Inline: True
Inline callers:
  - net/core/dev.c:netdev_boot_setup
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
In net/core/dev.c (ffffffff8210a916)
Location: net/core/dev.c:565
Inline: True
Inline callers:
  - net/core/dev.c:netdev_boot_setup
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
In net/core/dev.c (ffffffff827142be)
Location: net/core/dev.c:568
Inline: True
Inline callers:
  - net/core/dev.c:netdev_boot_setup
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
In net/core/dev.c (ffffffff8273e4b4)
Location: net/core/dev.c:568
Inline: True
Inline callers:
  - net/core/dev.c:netdev_boot_setup
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
In net/core/dev.c (ffffffff828f850c)
Location: net/core/dev.c:570
Inline: True
Inline callers:
  - net/core/dev.c:netdev_boot_setup
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
In net/core/dev.c (ffffffff82913f88)
Location: net/core/dev.c:566
Inline: True
Inline callers:
  - net/core/dev.c:netdev_boot_setup
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
In net/core/dev.c (ffffffff8291dd0b)
Location: net/core/dev.c:484
Inline: True
Inline callers:
  - net/core/dev.c:netdev_boot_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int netdev_boot_setup_add(char *name, struct ifmap *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0e7d1)
Location: net/core/dev.c:690
Inline: False
Direct callers:
  - net/core/dev.c:netdev_boot_setup
```
**Symbols:**

```
ffffffff81a0e7d1-ffffffff81a0e842: netdev_boot_setup_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int netdev_boot_setup_add(char *name, struct ifmap *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c30aaf)
Location: net/core/dev.c:693
Inline: False
Direct callers:
  - net/core/dev.c:netdev_boot_setup
```
**Symbols:**

```
ffffffff81c30aaf-ffffffff81c30b36: netdev_boot_setup_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int netdev_boot_setup_add(char *name, struct ifmap *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c22d96)
Location: net/core/dev.c:695
Inline: False
Direct callers:
  - net/core/dev.c:netdev_boot_setup
```
**Symbols:**

```
ffffffff81c22d96-ffffffff81c22e1c: netdev_boot_setup_add (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In net/core/dev.c (ffff8000114ae6fc)
Location: net/core/dev.c:484
Inline: True
Inline callers:
  - net/core/dev.c:netdev_boot_setup
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
In net/core/dev.c (c15b3354)
Location: net/core/dev.c:484
Inline: True
Inline callers:
  - net/core/dev.c:netdev_boot_setup
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
In net/core/dev.c (c0000000013be604)
Location: net/core/dev.c:484
Inline: True
Inline callers:
  - net/core/dev.c:netdev_boot_setup
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
In net/core/dev.c (ffffffe00003d9b4)
Location: net/core/dev.c:484
Inline: True
Inline callers:
  - net/core/dev.c:netdev_boot_setup
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
In net/core/dev.c (ffffffff82902a0f)
Location: net/core/dev.c:484
Inline: True
Inline callers:
  - net/core/dev.c:netdev_boot_setup
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
In net/core/dev.c (ffffffff828fad5d)
Location: net/core/dev.c:484
Inline: True
Inline callers:
  - net/core/dev.c:netdev_boot_setup
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
In net/core/dev.c (ffffffff82918016)
Location: net/core/dev.c:484
Inline: True
Inline callers:
  - net/core/dev.c:netdev_boot_setup
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
In net/core/dev.c (ffffffff8291ed6d)
Location: net/core/dev.c:484
Inline: True
Inline callers:
  - net/core/dev.c:netdev_boot_setup
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
</ul>

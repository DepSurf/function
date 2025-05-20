# Function: <code>devlink_trap_metadata_put</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81983a9d)
Location: net/core/devlink.c:5306
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_trap_metadata_put(struct sk_buff *msg, const struct devlink_trap *trap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5e5a0)
Location: net/core/devlink.c:5895
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_trap_fill
```
**Symbols:**

```
ffffffff81a5e5a0-ffffffff81a5e66b: devlink_trap_metadata_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_trap_metadata_put(struct sk_buff *msg, const struct devlink_trap *trap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a65400)
Location: net/core/devlink.c:6746
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_trap_fill
```
**Symbols:**

```
ffffffff81a65400-ffffffff81a654cb: devlink_trap_metadata_put (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81a4aebb)
Location: net/core/devlink.c:6949
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
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
In net/core/devlink.c (ffffffff81b03559)
Location: net/core/devlink.c:7575
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
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
In net/core/devlink.c (ffffffff81c84bce)
Location: net/core/devlink.c:8068
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
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
In net/core/devlink.c (ffffffff81e3ed2e)
Location: net/core/devlink.c:8603
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
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
In net/devlink/leftover.c (ffffffff8203f40e)
Location: net/devlink/leftover.c:5459
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_trap_fill
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
In net/devlink/trap.c (ffffffff82115fbc)
Location: net/devlink/trap.c:131
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_nl_trap_fill
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
In net/core/devlink.c (ffff800010c2c0fc)
Location: net/core/devlink.c:5306
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
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
In net/core/devlink.c (c0d42c84)
Location: net/core/devlink.c:5306
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
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
In net/core/devlink.c (c000000000d22c14)
Location: net/core/devlink.c:5306
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
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
In net/core/devlink.c (ffffffe0007a36ee)
Location: net/core/devlink.c:5306
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
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
In net/core/devlink.c (ffffffff8192390d)
Location: net/core/devlink.c:5306
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
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
In net/core/devlink.c (ffffffff818dd6bd)
Location: net/core/devlink.c:5306
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
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
In net/core/devlink.c (ffffffff81974a9d)
Location: net/core/devlink.c:5306
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
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
In net/core/devlink.c (ffffffff81996f8d)
Location: net/core/devlink.c:5306
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
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

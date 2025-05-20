# Function: <code>rproc_alloc_registered_carveouts</code>

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
In drivers/remoteproc/remoteproc_core.c (ffffffff818f5abe)
Location: drivers/remoteproc/remoteproc_core.c:1172
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rproc_alloc_registered_carveouts(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819cb5e1)
Location: drivers/remoteproc/remoteproc_core.c:1183
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
ffffffff819cb5e1-ffffffff819cb6d1: rproc_alloc_registered_carveouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rproc_alloc_registered_carveouts(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81c2e1c7)
Location: drivers/remoteproc/remoteproc_core.c:1241
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_actuate
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
ffffffff81c2e1c7-ffffffff81c2e2b7: rproc_alloc_registered_carveouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rproc_alloc_registered_carveouts(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81c202a0)
Location: drivers/remoteproc/remoteproc_core.c:1247
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
ffffffff81c202a0-ffffffff81c20390: rproc_alloc_registered_carveouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rproc_alloc_registered_carveouts(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d31c19)
Location: drivers/remoteproc/remoteproc_core.c:1263
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
ffffffff81d31c19-ffffffff81d31d09: rproc_alloc_registered_carveouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rproc_alloc_registered_carveouts(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81efe0f3)
Location: drivers/remoteproc/remoteproc_core.c:1259
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
ffffffff81efe0f3-ffffffff81efe1eb: rproc_alloc_registered_carveouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rproc_alloc_registered_carveouts(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d76610)
Location: drivers/remoteproc/remoteproc_core.c:1152
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
ffffffff81d76610-ffffffff81d76740: rproc_alloc_registered_carveouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rproc_alloc_registered_carveouts(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de4550)
Location: drivers/remoteproc/remoteproc_core.c:1153
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
ffffffff81de4550-ffffffff81de4680: rproc_alloc_registered_carveouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rproc_alloc_registered_carveouts(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9a640)
Location: drivers/remoteproc/remoteproc_core.c:1153
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
ffffffff81e9a640-ffffffff81e9a770: rproc_alloc_registered_carveouts (STB_LOCAL)
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
In drivers/remoteproc/remoteproc_core.c (ffff800010b81b30)
Location: drivers/remoteproc/remoteproc_core.c:1172
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
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
In drivers/remoteproc/remoteproc_core.c (c0c65058)
Location: drivers/remoteproc/remoteproc_core.c:1172
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
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
In drivers/remoteproc/remoteproc_core.c (c000000000c5e854)
Location: drivers/remoteproc/remoteproc_core.c:1172
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
</details>
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
In drivers/remoteproc/remoteproc_core.c (ffffffff81896dee)
Location: drivers/remoteproc/remoteproc_core.c:1172
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff8190754e)
Location: drivers/remoteproc/remoteproc_core.c:1172
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
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

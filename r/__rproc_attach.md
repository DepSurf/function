# Function: <code>__rproc_attach</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81c209e6)
Location: drivers/remoteproc/remoteproc_core.c:1425
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
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
In drivers/remoteproc/remoteproc_core.c (ffffffff81d323d2)
Location: drivers/remoteproc/remoteproc_core.c:1441
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
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
In drivers/remoteproc/remoteproc_core.c (ffffffff81efe8a1)
Location: drivers/remoteproc/remoteproc_core.c:1437
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __rproc_attach(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d78100)
Location: drivers/remoteproc/remoteproc_core.c:1330
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
```
**Symbols:**

```
ffffffff81d78100-ffffffff81d7823d: __rproc_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __rproc_attach(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de6050)
Location: drivers/remoteproc/remoteproc_core.c:1331
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
```
**Symbols:**

```
ffffffff81de6050-ffffffff81de618d: __rproc_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __rproc_attach(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9c230)
Location: drivers/remoteproc/remoteproc_core.c:1331
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
```
**Symbols:**

```
ffffffff81e9c230-ffffffff81e9c36d: __rproc_attach (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

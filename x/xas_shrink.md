# Function: <code>xas_shrink</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a188c8)
Location: lib/xarray.c:419
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In lib/xarray.c (ffffffff81a88576)
Location: lib/xarray.c:432
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In lib/xarray.c (ffffffff81abf816)
Location: lib/xarray.c:433
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xas_shrink(struct xa_state *xas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815fa470)
Location: lib/xarray.c:433
Inline: False
Direct callers:
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff815fa470-ffffffff815fa619: xas_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xas_shrink(struct xa_state *xas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8161ec60)
Location: lib/xarray.c:436
Inline: False
Direct callers:
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff8161ec60-ffffffff8161ee03: xas_shrink (STB_LOCAL)
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
In lib/xarray.c (ffffffff81603ecc)
Location: lib/xarray.c:436
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In lib/xarray.c (ffffffff8167260b)
Location: lib/xarray.c:436
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In lib/xarray.c (ffffffff8178ce60)
Location: lib/xarray.c:439
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In lib/xarray.c (ffffffff8204a48b)
Location: lib/xarray.c:439
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In lib/xarray.c (ffffffff820c8d82)
Location: lib/xarray.c:437
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In lib/xarray.c (ffffffff821a3702)
Location: lib/xarray.c:437
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In lib/xarray.c (ffff800010d9a984)
Location: lib/xarray.c:433
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In lib/xarray.c (c0e9750c)
Location: lib/xarray.c:433
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In lib/xarray.c (c000000000ee11cc)
Location: lib/xarray.c:433
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In lib/xarray.c (ffffffe0008c2f26)
Location: lib/xarray.c:433
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In lib/xarray.c (ffffffff81a5e666)
Location: lib/xarray.c:433
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In lib/xarray.c (ffffffff81a1b736)
Location: lib/xarray.c:433
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In lib/xarray.c (ffffffff81acaa56)
Location: lib/xarray.c:433
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In lib/xarray.c (ffffffff81ad7026)
Location: lib/xarray.c:433
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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

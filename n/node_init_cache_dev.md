# Function: <code>node_init_cache_dev</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff816f7be6)
Location: drivers/base/node.c:257
Inline: True
Inline callers:
  - drivers/base/node.c:node_add_cache
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
In drivers/base/node.c (ffffffff8171c046)
Location: drivers/base/node.c:257
Inline: True
Inline callers:
  - drivers/base/node.c:node_add_cache
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void node_init_cache_dev(struct node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff817d7db0)
Location: drivers/base/node.c:257
Inline: False
Direct callers:
  - drivers/base/node.c:node_add_cache
```
**Symbols:**

```
ffffffff817d7db0-ffffffff817d7e3f: node_init_cache_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void node_init_cache_dev(struct node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff817ec7c0)
Location: drivers/base/node.c:263
Inline: False
Direct callers:
  - drivers/base/node.c:node_add_cache
```
**Symbols:**

```
ffffffff817ec7c0-ffffffff817ec84f: node_init_cache_dev (STB_LOCAL)
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
In drivers/base/node.c (ffffffff817d1379)
Location: drivers/base/node.c:263
Inline: True
Inline callers:
  - drivers/base/node.c:node_add_cache
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
In drivers/base/node.c (ffffffff8185be49)
Location: drivers/base/node.c:267
Inline: True
Inline callers:
  - drivers/base/node.c:node_add_cache
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
In drivers/base/node.c (ffffffff819a2f43)
Location: drivers/base/node.c:267
Inline: True
Inline callers:
  - drivers/base/node.c:node_add_cache
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
In drivers/base/node.c (ffffffff81b14eb3)
Location: drivers/base/node.c:268
Inline: True
Inline callers:
  - drivers/base/node.c:node_add_cache
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
In drivers/base/node.c (ffffffff81b63c23)
Location: drivers/base/node.c:268
Inline: True
Inline callers:
  - drivers/base/node.c:node_add_cache
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
In drivers/base/node.c (ffffffff81bb779d)
Location: drivers/base/node.c:267
Inline: True
Inline callers:
  - drivers/base/node.c:node_add_cache
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
In drivers/base/node.c (ffff80001090fb64)
Location: drivers/base/node.c:257
Inline: True
Inline callers:
  - drivers/base/node.c:node_add_cache
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
In drivers/base/node.c (ffffffff816e2376)
Location: drivers/base/node.c:257
Inline: True
Inline callers:
  - drivers/base/node.c:node_add_cache
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
In drivers/base/node.c (ffffffff816bc9b6)
Location: drivers/base/node.c:257
Inline: True
Inline callers:
  - drivers/base/node.c:node_add_cache
```
</details>
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
In drivers/base/node.c (ffffffff8172a666)
Location: drivers/base/node.c:257
Inline: True
Inline callers:
  - drivers/base/node.c:node_add_cache
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

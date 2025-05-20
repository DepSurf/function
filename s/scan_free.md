# Function: <code>scan_free</code>

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
In drivers/nvdimm/namespace_devs.c (ffffffff8159c574)
Location: drivers/nvdimm/namespace_devs.c:416
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff815f25ef)
Location: drivers/nvdimm/namespace_devs.c:413
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff8161fe4d)
Location: drivers/nvdimm/namespace_devs.c:432
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff8163479e)
Location: drivers/nvdimm/namespace_devs.c:451
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff8169d11e)
Location: drivers/nvdimm/namespace_devs.c:451
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff816d9e18)
Location: drivers/nvdimm/namespace_devs.c:451
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff816fbdb5)
Location: drivers/nvdimm/namespace_devs.c:454
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff81735ce3)
Location: drivers/nvdimm/namespace_devs.c:446
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff81759a6c)
Location: drivers/nvdimm/namespace_devs.c:446
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int scan_free(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_label_id *label_id, resource_size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81816f80)
Location: drivers/nvdimm/namespace_devs.c:421
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff81816f80-ffffffff81817136: scan_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scan_free(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_label_id *label_id, resource_size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff818260b0)
Location: drivers/nvdimm/namespace_devs.c:421
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff818260b0-ffffffff81826266: scan_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int scan_free(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_label_id *label_id, resource_size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81809430)
Location: drivers/nvdimm/namespace_devs.c:421
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff81809430-ffffffff818095e6: scan_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int scan_free(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_label_id *label_id, resource_size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81893900)
Location: drivers/nvdimm/namespace_devs.c:421
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff81893900-ffffffff81893ab0: scan_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int scan_free(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_label_id *label_id, resource_size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff819dd850)
Location: drivers/nvdimm/namespace_devs.c:296
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff819dd850-ffffffff819dd9d6: scan_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int scan_free(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_label_id *label_id, resource_size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81b59090)
Location: drivers/nvdimm/namespace_devs.c:293
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff81b59090-ffffffff81b5921d: scan_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int scan_free(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_label_id *label_id, resource_size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81bac600)
Location: drivers/nvdimm/namespace_devs.c:293
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff81bac600-ffffffff81bac779: scan_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int scan_free(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_label_id *label_id, resource_size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81c00940)
Location: drivers/nvdimm/namespace_devs.c:296
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff81c00940-ffffffff81c00ab9: scan_free (STB_LOCAL)
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
In drivers/nvdimm/namespace_devs.c (ffff80001095b240)
Location: drivers/nvdimm/namespace_devs.c:446
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (c000000000a0bb70)
Location: drivers/nvdimm/namespace_devs.c:446
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffe0005c98a4)
Location: drivers/nvdimm/namespace_devs.c:446
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff8170e15c)
Location: drivers/nvdimm/namespace_devs.c:446
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff816e1bdc)
Location: drivers/nvdimm/namespace_devs.c:446
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff8174cf2c)
Location: drivers/nvdimm/namespace_devs.c:446
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff817683ac)
Location: drivers/nvdimm/namespace_devs.c:446
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
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

# Function: <code>dax_writeback_one</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81287394)
Location: fs/dax.c:670
Inline: True
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
In fs/dax.c (ffffffff8129b601)
Location: fs/dax.c:753
Inline: True
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
In fs/dax.c (ffffffff812aa419)
Location: fs/dax.c:653
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
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
In fs/dax.c (ffffffff812cdc45)
Location: fs/dax.c:661
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
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
In fs/dax.c (ffffffff812f83dd)
Location: fs/dax.c:931
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
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
In fs/dax.c (ffffffff8130ec9f)
Location: fs/dax.c:843
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
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
In fs/dax.c (ffffffff8133498e)
Location: fs/dax.c:848
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
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
In fs/dax.c (ffffffff81348561)
Location: fs/dax.c:849
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dax_writeback_one(struct xa_state *xas, struct dax_device *dax_dev, struct address_space *mapping, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8138da50)
Location: fs/dax.c:849
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff8138da50-ffffffff8138dc93: dax_writeback_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dax_writeback_one(struct xa_state *xas, struct dax_device *dax_dev, struct address_space *mapping, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8139f4c0)
Location: fs/dax.c:865
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff8139f4c0-ffffffff8139f6e3: dax_writeback_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dax_writeback_one(struct xa_state *xas, struct dax_device *dax_dev, struct address_space *mapping, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a6230)
Location: fs/dax.c:877
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff813a6230-ffffffff813a6455: dax_writeback_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dax_writeback_one(struct xa_state *xas, struct dax_device *dax_dev, struct address_space *mapping, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813f5ca0)
Location: fs/dax.c:877
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff813f5ca0-ffffffff813f5ec2: dax_writeback_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dax_writeback_one(struct xa_state *xas, struct dax_device *dax_dev, struct address_space *mapping, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814694c0)
Location: fs/dax.c:794
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff814694c0-ffffffff8146974e: dax_writeback_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dax_writeback_one(struct xa_state *xas, struct dax_device *dax_dev, struct address_space *mapping, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814f9f60)
Location: fs/dax.c:913
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff814f9f60-ffffffff814fa1d0: dax_writeback_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dax_writeback_one(struct xa_state *xas, struct dax_device *dax_dev, struct address_space *mapping, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff815313e0)
Location: fs/dax.c:940
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff815313e0-ffffffff8153164c: dax_writeback_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dax_writeback_one(struct xa_state *xas, struct dax_device *dax_dev, struct address_space *mapping, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff815662c0)
Location: fs/dax.c:926
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff815662c0-ffffffff8156652c: dax_writeback_one (STB_LOCAL)
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
In fs/dax.c (ffff80001040950c)
Location: fs/dax.c:849
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
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
In fs/dax.c (c000000000514b50)
Location: fs/dax.c:849
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
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
In fs/dax.c (ffffffe0002b4176)
Location: fs/dax.c:849
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
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
In fs/dax.c (ffffffff81340b41)
Location: fs/dax.c:849
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
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
In fs/dax.c (ffffffff81331531)
Location: fs/dax.c:849
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
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
In fs/dax.c (ffffffff8133e611)
Location: fs/dax.c:849
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
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
In fs/dax.c (ffffffff813514b1)
Location: fs/dax.c:849
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
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

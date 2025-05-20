# Function: <code>devm_register_dax_mapping</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devm_register_dax_mapping(struct dev_dax *dev_dax, int range_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81833710)
Location: drivers/dax/bus.c:712
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dev_dax_range
```
**Symbols:**

```
ffffffff81833710-ffffffff81833884: devm_register_dax_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devm_register_dax_mapping(struct dev_dax *dev_dax, int range_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81816870)
Location: drivers/dax/bus.c:713
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dev_dax_range
```
**Symbols:**

```
ffffffff81816870-ffffffff818169e4: devm_register_dax_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devm_register_dax_mapping(struct dev_dax *dev_dax, int range_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:711
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dev_dax_range
```
**Symbols:**

```
ffffffff818a0eb0-ffffffff818a1033: devm_register_dax_mapping (STB_LOCAL)
ffffffff81d0b941-ffffffff81d0b955: devm_register_dax_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devm_register_dax_mapping(struct dev_dax *dev_dax, int range_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:741
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dev_dax_range
```
**Symbols:**

```
ffffffff819ea550-ffffffff819ea6e9: devm_register_dax_mapping (STB_LOCAL)
ffffffff81ed4750-ffffffff81ed476c: devm_register_dax_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int devm_register_dax_mapping(struct dev_dax *dev_dax, int range_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:741
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dev_dax_range
```
**Symbols:**

```
ffffffff81b66ff0-ffffffff81b67189: devm_register_dax_mapping (STB_LOCAL)
ffffffff8209b5d0-ffffffff8209b5ec: devm_register_dax_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int devm_register_dax_mapping(struct dev_dax *dev_dax, int range_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:770
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dev_dax_range
```
**Symbols:**

```
ffffffff81bba6e0-ffffffff81bba86c: devm_register_dax_mapping (STB_LOCAL)
ffffffff8211c4ac-ffffffff8211c4c0: devm_register_dax_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int devm_register_dax_mapping(struct dev_dax *dev_dax, int range_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:771
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dev_dax_range
```
**Symbols:**

```
ffffffff81c0eb70-ffffffff81c0ed2b: devm_register_dax_mapping (STB_LOCAL)
ffffffff821fa333-ffffffff821fa347: devm_register_dax_mapping.cold (STB_LOCAL)
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

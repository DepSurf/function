# Function: <code>devm_create_dev_dax</code>

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
struct dev_dax *devm_create_dev_dax(struct dev_dax_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff818349b0)
Location: drivers/dax/bus.c:1270
Inline: False
Direct callers:
  - drivers/dax/bus.c:create_store
```
**Symbols:**

```
ffffffff818349b0-ffffffff81834df0: devm_create_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dev_dax *devm_create_dev_dax(struct dev_dax_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81817b80)
Location: drivers/dax/bus.c:1271
Inline: False
Direct callers:
  - drivers/dax/bus.c:create_store
```
**Symbols:**

```
ffffffff81817b80-ffffffff81817fbc: devm_create_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dev_dax *devm_create_dev_dax(struct dev_dax_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:1269
Inline: False
Direct callers:
  - drivers/dax/bus.c:create_store
```
**Symbols:**

```
ffffffff81d0b991-ffffffff81d0b9d4: devm_create_dev_dax.cold (STB_LOCAL)
ffffffff818a21d0-ffffffff818a262a: devm_create_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dev_dax *devm_create_dev_dax(struct dev_dax_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:1299
Inline: False
Direct callers:
  - drivers/dax/bus.c:create_store
```
**Symbols:**

```
ffffffff81ed47b2-ffffffff81ed47ff: devm_create_dev_dax.cold (STB_LOCAL)
ffffffff819eb9d0-ffffffff819ebe11: devm_create_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct dev_dax *devm_create_dev_dax(struct dev_dax_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:1299
Inline: False
Direct callers:
  - drivers/dax/bus.c:create_store
```
**Symbols:**

```
ffffffff8209b632-ffffffff8209b676: devm_create_dev_dax.cold (STB_LOCAL)
ffffffff81b68590-ffffffff81b689ef: devm_create_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct dev_dax *devm_create_dev_dax(struct dev_dax_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:1327
Inline: False
Direct callers:
  - drivers/dax/bus.c:create_store
```
**Symbols:**

```
ffffffff8211c4ff-ffffffff8211c53b: devm_create_dev_dax.cold (STB_LOCAL)
ffffffff81bbba20-ffffffff81bbbe62: devm_create_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct dev_dax *devm_create_dev_dax(struct dev_dax_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:1328
Inline: False
Direct callers:
  - drivers/dax/bus.c:create_store
```
**Symbols:**

```
ffffffff821fa386-ffffffff821fa3d7: devm_create_dev_dax.cold (STB_LOCAL)
ffffffff81c10160-ffffffff81c105ea: devm_create_dev_dax (STB_GLOBAL)
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

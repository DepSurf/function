# Function: <code>unregister_dax_mapping</code>

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
void unregister_dax_mapping(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81832ab0)
Location: drivers/dax/bus.c:601
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_register_dax_mapping
```
**Symbols:**

```
ffffffff81832ab0-ffffffff81832b23: unregister_dax_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unregister_dax_mapping(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81815cf0)
Location: drivers/dax/bus.c:602
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_register_dax_mapping
```
**Symbols:**

```
ffffffff81815cf0-ffffffff81815d63: unregister_dax_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void unregister_dax_mapping(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff818a0330)
Location: drivers/dax/bus.c:600
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_register_dax_mapping
```
**Symbols:**

```
ffffffff818a0330-ffffffff818a03a0: unregister_dax_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void unregister_dax_mapping(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff819e9920)
Location: drivers/dax/bus.c:630
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_register_dax_mapping
```
**Symbols:**

```
ffffffff819e9920-ffffffff819e999c: unregister_dax_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unregister_dax_mapping(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81b662d0)
Location: drivers/dax/bus.c:630
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_register_dax_mapping
```
**Symbols:**

```
ffffffff81b662d0-ffffffff81b6634c: unregister_dax_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void unregister_dax_mapping(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81bb9d30)
Location: drivers/dax/bus.c:660
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_register_dax_mapping
```
**Symbols:**

```
ffffffff81bb9d30-ffffffff81bb9da4: unregister_dax_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void unregister_dax_mapping(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81c0e390)
Location: drivers/dax/bus.c:661
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_register_dax_mapping
```
**Symbols:**

```
ffffffff81c0e390-ffffffff81c0e404: unregister_dax_mapping (STB_LOCAL)
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

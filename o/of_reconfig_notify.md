# Function: <code>of_reconfig_notify</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int of_reconfig_notify(long unsigned int action, struct of_reconfig_data *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (ffff800010b70bb4)
Location: drivers/of/dynamic.c:76
Inline: True
Inline callers:
  - drivers/of/dynamic.c:__of_changeset_entry_notify
  - drivers/of/dynamic.c:of_detach_node
  - drivers/of/dynamic.c:of_attach_node
```
**Symbols:**

```
ffff800010b709e8-ffff800010b70a38: of_reconfig_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int of_reconfig_notify(long unsigned int action, struct of_reconfig_data *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (c0c53360)
Location: drivers/of/dynamic.c:76
Inline: True
Inline callers:
  - drivers/of/dynamic.c:__of_changeset_entry_notify
  - drivers/of/dynamic.c:of_detach_node
  - drivers/of/dynamic.c:of_attach_node
```
**Symbols:**

```
c0c531a8-c0c531e4: of_reconfig_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int of_reconfig_notify(long unsigned int action, struct of_reconfig_data *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (c000000000c4c654)
Location: drivers/of/dynamic.c:76
Inline: True
Inline callers:
  - drivers/of/dynamic.c:__of_changeset_entry_notify
  - drivers/of/dynamic.c:of_detach_node
  - drivers/of/dynamic.c:of_attach_node
```
**Symbols:**

```
c000000000c4c3e0-c000000000c4c454: of_reconfig_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int of_reconfig_notify(long unsigned int action, struct of_reconfig_data *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (ffffffe000724c0c)
Location: drivers/of/dynamic.c:76
Inline: True
Inline callers:
  - drivers/of/dynamic.c:__of_changeset_entry_notify
  - drivers/of/dynamic.c:of_detach_node
  - drivers/of/dynamic.c:of_attach_node
```
**Symbols:**

```
ffffffe000724ac0-ffffffe000724b1a: of_reconfig_notify (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>

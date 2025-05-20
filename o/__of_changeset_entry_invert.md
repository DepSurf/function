# Function: <code>__of_changeset_entry_invert</code>

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
void __of_changeset_entry_invert(struct of_changeset_entry *ce, struct of_changeset_entry *rce);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (ffff800010b706f8)
Location: drivers/of/dynamic.c:501
Inline: True
Direct callers:
  - drivers/of/dynamic.c:__of_changeset_revert_entries
  - drivers/of/dynamic.c:__of_changeset_apply_entries
  - drivers/of/dynamic.c:__of_changeset_entry_notify
```
**Symbols:**

```
ffff800010b706f8-ffff800010b707e0: __of_changeset_entry_invert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __of_changeset_entry_invert(struct of_changeset_entry *ce, struct of_changeset_entry *rce);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (c0c530e4)
Location: drivers/of/dynamic.c:501
Inline: True
Direct callers:
  - drivers/of/dynamic.c:__of_changeset_revert_entries
  - drivers/of/dynamic.c:__of_changeset_apply_entries
  - drivers/of/dynamic.c:__of_changeset_entry_notify
```
**Symbols:**

```
c0c530e4-c0c531a8: __of_changeset_entry_invert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __of_changeset_entry_invert(struct of_changeset_entry *ce, struct of_changeset_entry *rce);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (c000000000c4c1f0)
Location: drivers/of/dynamic.c:501
Inline: True
Direct callers:
  - drivers/of/dynamic.c:__of_changeset_revert_entries
  - drivers/of/dynamic.c:__of_changeset_apply_entries
  - drivers/of/dynamic.c:__of_changeset_entry_notify
```
**Symbols:**

```
c000000000c4c1f0-c000000000c4c2dc: __of_changeset_entry_invert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __of_changeset_entry_invert(struct of_changeset_entry *ce, struct of_changeset_entry *rce);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (ffffffe000724a0e)
Location: drivers/of/dynamic.c:501
Inline: True
Direct callers:
  - drivers/of/dynamic.c:__of_changeset_revert_entries
  - drivers/of/dynamic.c:__of_changeset_apply_entries
  - drivers/of/dynamic.c:__of_changeset_entry_notify
```
**Symbols:**

```
ffffffe000724a0e-ffffffe000724ac0: __of_changeset_entry_invert (STB_LOCAL)
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

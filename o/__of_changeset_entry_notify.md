# Function: <code>__of_changeset_entry_notify</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
int __of_changeset_entry_notify(struct of_changeset_entry *ce, bool revert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (ffff800010b70ae0)
Location: drivers/of/dynamic.c:531
Inline: False
Direct callers:
  - drivers/of/dynamic.c:__of_changeset_revert_notify
  - drivers/of/dynamic.c:__of_changeset_apply_notify
```
**Symbols:**

```
ffff800010b70ae0-ffff800010b70bec: __of_changeset_entry_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __of_changeset_entry_notify(struct of_changeset_entry *ce, bool revert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (c0c53284)
Location: drivers/of/dynamic.c:531
Inline: False
```
**Symbols:**

```
c0c53284-c0c53390: __of_changeset_entry_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __of_changeset_entry_notify(struct of_changeset_entry *ce, bool revert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (c000000000c4c550)
Location: drivers/of/dynamic.c:531
Inline: False
```
**Symbols:**

```
c000000000c4c550-c000000000c4c698: __of_changeset_entry_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __of_changeset_entry_notify(struct of_changeset_entry *ce, bool revert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (ffffffe000724b9e)
Location: drivers/of/dynamic.c:531
Inline: False
```
**Symbols:**

```
ffffffe000724b9e-ffffffe000724c6c: __of_changeset_entry_notify (STB_LOCAL)
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

# Function: <code>vc_selection_store_chars</code>

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
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int vc_selection_store_chars(struct vc_data *vc, bool unicode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/selection.c (0)
Location: drivers/tty/vt/selection.c:188
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:vc_do_selection
```
**Symbols:**

```
ffffffff81747440-ffffffff81747639: vc_selection_store_chars (STB_LOCAL)
ffffffff81747c30-ffffffff81747c4b: vc_selection_store_chars.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int vc_selection_store_chars(struct vc_data *vc, bool unicode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/selection.c (0)
Location: drivers/tty/vt/selection.c:188
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:vc_do_selection
```
**Symbols:**

```
ffffffff81762d90-ffffffff81762f89: vc_selection_store_chars (STB_LOCAL)
ffffffff81c078e0-ffffffff81c078fb: vc_selection_store_chars.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int vc_selection_store_chars(struct vc_data *vc, bool unicode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/selection.c (0)
Location: drivers/tty/vt/selection.c:188
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:vc_do_selection
```
**Symbols:**

```
ffffffff81746a50-ffffffff81746c49: vc_selection_store_chars (STB_LOCAL)
ffffffff81bf951a-ffffffff81bf9535: vc_selection_store_chars.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vc_selection_store_chars(struct vc_data *vc, bool unicode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/selection.c (0)
Location: drivers/tty/vt/selection.c:188
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:vc_do_selection
```
**Symbols:**

```
ffffffff817c7a40-ffffffff817c7c39: vc_selection_store_chars (STB_LOCAL)
ffffffff81cf9295-ffffffff81cf92b0: vc_selection_store_chars.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vc_selection_store_chars(struct vc_data *vc, bool unicode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/selection.c (0)
Location: drivers/tty/vt/selection.c:188
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:vc_do_selection
```
**Symbols:**

```
ffffffff81904b80-ffffffff81904d92: vc_selection_store_chars (STB_LOCAL)
ffffffff81ec145a-ffffffff81ec1475: vc_selection_store_chars.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vc_selection_store_chars(struct vc_data *vc, bool unicode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff81a5ec90)
Location: drivers/tty/vt/selection.c:189
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:vc_do_selection
```
**Symbols:**

```
ffffffff81a5ec90-ffffffff81a5eed3: vc_selection_store_chars (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vc_selection_store_chars(struct vc_data *vc, bool unicode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff81aa9330)
Location: drivers/tty/vt/selection.c:189
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:vc_do_selection
```
**Symbols:**

```
ffffffff81aa9330-ffffffff81aa9551: vc_selection_store_chars (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vc_selection_store_chars(struct vc_data *vc, bool unicode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff81afbdf0)
Location: drivers/tty/vt/selection.c:189
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:vc_do_selection
```
**Symbols:**

```
ffffffff81afbdf0-ffffffff81afc011: vc_selection_store_chars (STB_LOCAL)
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

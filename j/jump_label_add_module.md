# Function: <code>jump_label_add_module</code>

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
In kernel/jump_label.c (ffffffff8118b17b)
Location: kernel/jump_label.c:305
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
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
In kernel/jump_label.c (ffffffff8119d899)
Location: kernel/jump_label.c:394
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
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
In kernel/jump_label.c (ffffffff811ad2b9)
Location: kernel/jump_label.c:401
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
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
In kernel/jump_label.c (ffffffff811b471f)
Location: kernel/jump_label.c:474
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
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
In kernel/jump_label.c (ffffffff811c852f)
Location: kernel/jump_label.c:528
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
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
In kernel/jump_label.c (ffffffff811e8a3f)
Location: kernel/jump_label.c:546
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
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
In kernel/jump_label.c (ffffffff811f973b)
Location: kernel/jump_label.c:551
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
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
In kernel/jump_label.c (ffffffff8121168b)
Location: kernel/jump_label.c:605
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
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
In kernel/jump_label.c (ffffffff8121ea4b)
Location: kernel/jump_label.c:607
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int jump_label_add_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8124af20)
Location: kernel/jump_label.c:607
Inline: False
Direct callers:
  - kernel/jump_label.c:jump_label_module_notify
```
**Symbols:**

```
ffffffff8124af20-ffffffff8124b16c: jump_label_add_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int jump_label_add_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81255380)
Location: kernel/jump_label.c:621
Inline: False
Direct callers:
  - kernel/jump_label.c:jump_label_module_notify
```
**Symbols:**

```
ffffffff81255380-ffffffff812555cc: jump_label_add_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int jump_label_add_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81259880)
Location: kernel/jump_label.c:623
Inline: False
Direct callers:
  - kernel/jump_label.c:jump_label_module_notify
```
**Symbols:**

```
ffffffff81259880-ffffffff81259acb: jump_label_add_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int jump_label_add_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81295590)
Location: kernel/jump_label.c:624
Inline: False
Direct callers:
  - kernel/jump_label.c:jump_label_module_notify
```
**Symbols:**

```
ffffffff81295590-ffffffff81295800: jump_label_add_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int jump_label_add_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812eb390)
Location: kernel/jump_label.c:624
Inline: False
Direct callers:
  - kernel/jump_label.c:jump_label_module_notify
```
**Symbols:**

```
ffffffff812eb390-ffffffff812eb616: jump_label_add_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int jump_label_add_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81355450)
Location: kernel/jump_label.c:623
Inline: False
Direct callers:
  - kernel/jump_label.c:jump_label_module_notify
```
**Symbols:**

```
ffffffff81355450-ffffffff813556d6: jump_label_add_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int jump_label_add_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81386940)
Location: kernel/jump_label.c:623
Inline: False
Direct callers:
  - kernel/jump_label.c:jump_label_module_notify
```
**Symbols:**

```
ffffffff81386940-ffffffff81386d54: jump_label_add_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int jump_label_add_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff813afe00)
Location: kernel/jump_label.c:623
Inline: False
Direct callers:
  - kernel/jump_label.c:jump_label_module_notify
```
**Symbols:**

```
ffffffff813afe00-ffffffff813b0266: jump_label_add_module (STB_LOCAL)
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
In kernel/jump_label.c (ffff8000102aabe8)
Location: kernel/jump_label.c:607
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
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
In kernel/jump_label.c (c00000000035f208)
Location: kernel/jump_label.c:607
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
```
</details>
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
In kernel/jump_label.c (ffffffff8121709b)
Location: kernel/jump_label.c:607
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
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
In kernel/jump_label.c (ffffffff81209dfb)
Location: kernel/jump_label.c:607
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
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
In kernel/jump_label.c (ffffffff81214e3b)
Location: kernel/jump_label.c:607
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
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
In kernel/jump_label.c (ffffffff81223deb)
Location: kernel/jump_label.c:607
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
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

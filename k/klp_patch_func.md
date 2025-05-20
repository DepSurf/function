# Function: <code>klp_patch_func</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff810f896b)
Location: kernel/livepatch/patch.c:171
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
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
In kernel/livepatch/patch.c (ffffffff81102bab)
Location: kernel/livepatch/patch.c:172
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
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
In kernel/livepatch/patch.c (ffffffff8110b19c)
Location: kernel/livepatch/patch.c:172
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
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
In kernel/livepatch/patch.c (ffffffff8111698c)
Location: kernel/livepatch/patch.c:172
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
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
In kernel/livepatch/patch.c (ffffffff81120bec)
Location: kernel/livepatch/patch.c:169
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
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
In kernel/livepatch/patch.c (ffffffff8112d2bc)
Location: kernel/livepatch/patch.c:169
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int klp_patch_func(struct klp_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:169
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:klp_patch_object
```
**Symbols:**

```
ffffffff8113b870-ffffffff8113b9cd: klp_patch_func (STB_LOCAL)
ffffffff8113bbe2-ffffffff8113bc61: klp_patch_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int klp_patch_func(struct klp_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:174
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:klp_patch_object
```
**Symbols:**

```
ffffffff81136010-ffffffff8113616d: klp_patch_func (STB_LOCAL)
ffffffff81be330c-ffffffff81be338b: klp_patch_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int klp_patch_func(struct klp_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:174
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:klp_patch_object
```
**Symbols:**

```
ffffffff81136e10-ffffffff81136f6d: klp_patch_func (STB_LOCAL)
ffffffff81bd51dc-ffffffff81bd525b: klp_patch_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int klp_patch_func(struct klp_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:174
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:klp_patch_object
```
**Symbols:**

```
ffffffff81159ae0-ffffffff81159c57: klp_patch_func (STB_LOCAL)
ffffffff81cafed1-ffffffff81caff7f: klp_patch_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int klp_patch_func(struct klp_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:160
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:klp_patch_object
```
**Symbols:**

```
ffffffff811830f0-ffffffff81183269: klp_patch_func (STB_LOCAL)
ffffffff81e60ae7-ffffffff81e60b8f: klp_patch_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int klp_patch_func(struct klp_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:160
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:klp_patch_object
```
**Symbols:**

```
ffffffff811be170-ffffffff811be374: klp_patch_func (STB_LOCAL)
ffffffff8205a61f-ffffffff8205a634: klp_patch_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int klp_patch_func(struct klp_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:160
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:klp_patch_object
```
**Symbols:**

```
ffffffff811d0ba0-ffffffff811d0da4: klp_patch_func (STB_LOCAL)
ffffffff820d8e93-ffffffff820d8ea8: klp_patch_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int klp_patch_func(struct klp_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:160
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:klp_patch_object
```
**Symbols:**

```
ffffffff811e57f0-ffffffff811e5a23: klp_patch_func (STB_LOCAL)
ffffffff821b45cc-ffffffff821b45e1: klp_patch_func.cold (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (c0000000001f1cd0)
Location: kernel/livepatch/patch.c:169
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
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
In kernel/livepatch/patch.c (ffffffff8112589c)
Location: kernel/livepatch/patch.c:169
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
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
In kernel/livepatch/patch.c (ffffffff811182fc)
Location: kernel/livepatch/patch.c:169
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
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
In kernel/livepatch/patch.c (ffffffff8112378c)
Location: kernel/livepatch/patch.c:169
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
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
In kernel/livepatch/patch.c (ffffffff8112fdac)
Location: kernel/livepatch/patch.c:169
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
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

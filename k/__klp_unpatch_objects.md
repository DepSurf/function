# Function: <code>__klp_unpatch_objects</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __klp_unpatch_objects(struct klp_patch *patch, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff81120af0)
Location: kernel/livepatch/patch.c:279
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:klp_unpatch_objects_dynamic
  - kernel/livepatch/patch.c:klp_unpatch_objects
```
**Symbols:**

```
ffffffff81120af0-ffffffff81120b48: __klp_unpatch_objects (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __klp_unpatch_objects(struct klp_patch *patch, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff8112d1c0)
Location: kernel/livepatch/patch.c:279
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:klp_unpatch_objects_dynamic
  - kernel/livepatch/patch.c:klp_unpatch_objects
```
**Symbols:**

```
ffffffff8112d1c0-ffffffff8112d218: __klp_unpatch_objects (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff8113bb95)
Location: kernel/livepatch/patch.c:280
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_unpatch_objects_dynamic
  - kernel/livepatch/patch.c:klp_unpatch_objects
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff81136335)
Location: kernel/livepatch/patch.c:287
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_unpatch_objects_dynamic
  - kernel/livepatch/patch.c:klp_unpatch_objects
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff81137135)
Location: kernel/livepatch/patch.c:287
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_unpatch_objects_dynamic
  - kernel/livepatch/patch.c:klp_unpatch_objects
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff81159dd5)
Location: kernel/livepatch/patch.c:287
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_unpatch_objects_dynamic
  - kernel/livepatch/patch.c:klp_unpatch_objects
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff81183405)
Location: kernel/livepatch/patch.c:272
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_unpatch_objects_dynamic
  - kernel/livepatch/patch.c:klp_unpatch_objects
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff811be565)
Location: kernel/livepatch/patch.c:272
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_unpatch_objects_dynamic
  - kernel/livepatch/patch.c:klp_unpatch_objects
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff811d0f95)
Location: kernel/livepatch/patch.c:272
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_unpatch_objects_dynamic
  - kernel/livepatch/patch.c:klp_unpatch_objects
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff811e5c15)
Location: kernel/livepatch/patch.c:272
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_unpatch_objects_dynamic
  - kernel/livepatch/patch.c:klp_unpatch_objects
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
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __klp_unpatch_objects(struct klp_patch *patch, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (c0000000001f1b00)
Location: kernel/livepatch/patch.c:279
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:klp_unpatch_objects_dynamic
  - kernel/livepatch/patch.c:klp_unpatch_objects
```
**Symbols:**

```
c0000000001f1b00-c0000000001f1ba4: __klp_unpatch_objects (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void __klp_unpatch_objects(struct klp_patch *patch, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff811257a0)
Location: kernel/livepatch/patch.c:279
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:klp_unpatch_objects_dynamic
  - kernel/livepatch/patch.c:klp_unpatch_objects
```
**Symbols:**

```
ffffffff811257a0-ffffffff811257f8: __klp_unpatch_objects (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __klp_unpatch_objects(struct klp_patch *patch, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff81118200)
Location: kernel/livepatch/patch.c:279
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:klp_unpatch_objects_dynamic
  - kernel/livepatch/patch.c:klp_unpatch_objects
```
**Symbols:**

```
ffffffff81118200-ffffffff81118258: __klp_unpatch_objects (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __klp_unpatch_objects(struct klp_patch *patch, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff81123690)
Location: kernel/livepatch/patch.c:279
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:klp_unpatch_objects_dynamic
  - kernel/livepatch/patch.c:klp_unpatch_objects
```
**Symbols:**

```
ffffffff81123690-ffffffff811236e8: __klp_unpatch_objects (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __klp_unpatch_objects(struct klp_patch *patch, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff8112fcb0)
Location: kernel/livepatch/patch.c:279
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:klp_unpatch_objects_dynamic
  - kernel/livepatch/patch.c:klp_unpatch_objects
```
**Symbols:**

```
ffffffff8112fcb0-ffffffff8112fd08: __klp_unpatch_objects (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>

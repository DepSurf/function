# Function: <code>__klp_disable_patch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810e8ab0)
Location: kernel/livepatch/core.c:420
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_disable_patch
  - kernel/livepatch/core.c:enabled_store
Direct callers:
  - kernel/livepatch/core.c:klp_disable_patch
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff810e8ab0-ffffffff810e8b3c: __klp_disable_patch.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810f00a6)
Location: kernel/livepatch/core.c:484
Inline: True
Inline callers:
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/core.c:klp_disable_patch
Direct callers:
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/core.c:klp_disable_patch
```
**Symbols:**

```
ffffffff810ef1b0-ffffffff810ef210: __klp_disable_patch.part.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810f6c56)
Location: kernel/livepatch/core.c:482
Inline: True
Inline callers:
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/core.c:klp_disable_patch
Direct callers:
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/core.c:klp_disable_patch
```
**Symbols:**

```
ffffffff810f6320-ffffffff810f6380: __klp_disable_patch.part.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __klp_disable_patch(struct klp_patch *patch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810f7570)
Location: kernel/livepatch/core.c:286
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/core.c:klp_disable_patch
```
**Symbols:**

```
ffffffff810f7570-ffffffff810f75bb: __klp_disable_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __klp_disable_patch(struct klp_patch *patch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81101610)
Location: kernel/livepatch/core.c:281
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/core.c:klp_disable_patch
```
**Symbols:**

```
ffffffff81101610-ffffffff811016a6: __klp_disable_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __klp_disable_patch(struct klp_patch *patch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81109a60)
Location: kernel/livepatch/core.c:281
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/core.c:klp_disable_patch
```
**Symbols:**

```
ffffffff81109a60-ffffffff81109af7: __klp_disable_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __klp_disable_patch(struct klp_patch *patch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81115230)
Location: kernel/livepatch/core.c:281
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/core.c:klp_disable_patch
```
**Symbols:**

```
ffffffff81115230-ffffffff811152c7: __klp_disable_patch (STB_LOCAL)
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
In kernel/livepatch/core.c (ffffffff8111f290)
Location: kernel/livepatch/core.c:872
Inline: True
Inline callers:
  - kernel/livepatch/core.c:enabled_store
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
In kernel/livepatch/core.c (ffffffff8112b9d0)
Location: kernel/livepatch/core.c:872
Inline: True
Inline callers:
  - kernel/livepatch/core.c:enabled_store
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
In kernel/livepatch/core.c (ffffffff8113a110)
Location: kernel/livepatch/core.c:925
Inline: True
Inline callers:
  - kernel/livepatch/core.c:enabled_store
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
In kernel/livepatch/core.c (ffffffff81134c00)
Location: kernel/livepatch/core.c:925
Inline: True
Inline callers:
  - kernel/livepatch/core.c:enabled_store
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
In kernel/livepatch/core.c (ffffffff81135ad0)
Location: kernel/livepatch/core.c:924
Inline: True
Inline callers:
  - kernel/livepatch/core.c:enabled_store
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
In kernel/livepatch/core.c (ffffffff811586f4)
Location: kernel/livepatch/core.c:924
Inline: True
Inline callers:
  - kernel/livepatch/core.c:enabled_store
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
In kernel/livepatch/core.c (ffffffff81181c24)
Location: kernel/livepatch/core.c:913
Inline: True
Inline callers:
  - kernel/livepatch/core.c:enabled_store
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
In kernel/livepatch/core.c (ffffffff811bc524)
Location: kernel/livepatch/core.c:938
Inline: True
Inline callers:
  - kernel/livepatch/core.c:enabled_store
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
In kernel/livepatch/core.c (ffffffff811ceec4)
Location: kernel/livepatch/core.c:966
Inline: True
Inline callers:
  - kernel/livepatch/core.c:enabled_store
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
In kernel/livepatch/core.c (ffffffff811e3aa4)
Location: kernel/livepatch/core.c:966
Inline: True
Inline callers:
  - kernel/livepatch/core.c:enabled_store
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
In kernel/livepatch/core.c (c0000000001eede0)
Location: kernel/livepatch/core.c:872
Inline: True
Inline callers:
  - kernel/livepatch/core.c:enabled_store
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
In kernel/livepatch/core.c (ffffffff81123fb0)
Location: kernel/livepatch/core.c:872
Inline: True
Inline callers:
  - kernel/livepatch/core.c:enabled_store
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
In kernel/livepatch/core.c (ffffffff81116a10)
Location: kernel/livepatch/core.c:872
Inline: True
Inline callers:
  - kernel/livepatch/core.c:enabled_store
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
In kernel/livepatch/core.c (ffffffff81121ea0)
Location: kernel/livepatch/core.c:872
Inline: True
Inline callers:
  - kernel/livepatch/core.c:enabled_store
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
In kernel/livepatch/core.c (ffffffff8112e4b0)
Location: kernel/livepatch/core.c:872
Inline: True
Inline callers:
  - kernel/livepatch/core.c:enabled_store
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>

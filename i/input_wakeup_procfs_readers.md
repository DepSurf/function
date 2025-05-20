# Function: <code>input_wakeup_procfs_readers</code>

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
In drivers/input/input.c (ffffffff81667ecb)
Location: drivers/input/input.c:1052
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
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
In drivers/input/input.c (ffffffff816c7d49)
Location: drivers/input/input.c:1051
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
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
In drivers/input/input.c (ffffffff816f5d39)
Location: drivers/input/input.c:1051
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
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
In drivers/input/input.c (ffffffff8170b899)
Location: drivers/input/input.c:1051
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
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
In drivers/input/input.c (ffffffff8177c8ae)
Location: drivers/input/input.c:1045
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
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
In drivers/input/input.c (ffffffff817bd979)
Location: drivers/input/input.c:1053
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
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
In drivers/input/input.c (ffffffff817e4dd9)
Location: drivers/input/input.c:1053
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
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
In drivers/input/input.c (ffffffff8182583d)
Location: drivers/input/input.c:1049
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
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
In drivers/input/input.c (ffffffff81856d69)
Location: drivers/input/input.c:1080
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void input_wakeup_procfs_readers();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81929fc9)
Location: drivers/input/input.c:1080
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff81928e70-ffffffff81928e95: input_wakeup_procfs_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void input_wakeup_procfs_readers();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81931539)
Location: drivers/input/input.c:1084
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff81930470-ffffffff81930495: input_wakeup_procfs_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void input_wakeup_procfs_readers();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81914b79)
Location: drivers/input/input.c:1084
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff819136d0-ffffffff819136f5: input_wakeup_procfs_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void input_wakeup_procfs_readers();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff819b6d09)
Location: drivers/input/input.c:1084
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff819b54e0-ffffffff819b5505: input_wakeup_procfs_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void input_wakeup_procfs_readers();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81b16799)
Location: drivers/input/input.c:1131
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff81b14ef0-ffffffff81b14f21: input_wakeup_procfs_readers (STB_LOCAL)
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
In drivers/input/input.c (ffffffff81ca7af9)
Location: drivers/input/input.c:1110
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
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
In drivers/input/input.c (ffffffff81d0f009)
Location: drivers/input/input.c:1113
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
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
In drivers/input/input.c (ffffffff81dc4d29)
Location: drivers/input/input.c:1113
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
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
In drivers/input/input.c (ffff800010a95f98)
Location: drivers/input/input.c:1080
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (c0b78c58)
Location: drivers/input/input.c:1080
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (c000000000b755e0)
Location: drivers/input/input.c:1080
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffe0006a7a1e)
Location: drivers/input/input.c:1080
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
```
</details>
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
In drivers/input/input.c (ffffffff8180bd79)
Location: drivers/input/input.c:1080
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
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
In drivers/input/input.c (ffffffff817d34e9)
Location: drivers/input/input.c:1080
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
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
In drivers/input/input.c (ffffffff8184aef9)
Location: drivers/input/input.c:1080
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
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
In drivers/input/input.c (ffffffff81866149)
Location: drivers/input/input.c:1080
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
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
</ul>

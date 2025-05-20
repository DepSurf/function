# Function: <code>kgdb_unregister_io_module</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kgdb_unregister_io_module(struct kgdb_io *old_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8112f760)
Location: kernel/debug/debug_core.c:1025
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff8112f760-ffffffff8112f869: kgdb_unregister_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void kgdb_unregister_io_module(struct kgdb_io *old_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81137b40)
Location: kernel/debug/debug_core.c:1025
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff81137b40-ffffffff81137c49: kgdb_unregister_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void kgdb_unregister_io_module(struct kgdb_io *old_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811418d0)
Location: kernel/debug/debug_core.c:1025
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff811418d0-ffffffff811419d9: kgdb_unregister_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void kgdb_unregister_io_module(struct kgdb_io *old_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81143130)
Location: kernel/debug/debug_core.c:1026
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff81143130-ffffffff81143216: kgdb_unregister_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kgdb_unregister_io_module(struct kgdb_io *old_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8114fcf0)
Location: kernel/debug/debug_core.c:1026
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff8114fcf0-ffffffff8114fdd6: kgdb_unregister_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void kgdb_unregister_io_module(struct kgdb_io *old_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8115ea00)
Location: kernel/debug/debug_core.c:1026
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff8115ea00-ffffffff8115eae6: kgdb_unregister_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void kgdb_unregister_io_module(struct kgdb_io *old_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8116b690)
Location: kernel/debug/debug_core.c:1089
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff8116b690-ffffffff8116b776: kgdb_unregister_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void kgdb_unregister_io_module(struct kgdb_io *old_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81178480)
Location: kernel/debug/debug_core.c:1089
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff81178480-ffffffff81178566: kgdb_unregister_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void kgdb_unregister_io_module(struct kgdb_io *old_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811842e0)
Location: kernel/debug/debug_core.c:1077
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff811842e0-ffffffff811843b3: kgdb_unregister_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void kgdb_unregister_io_module(struct kgdb_io *old_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:1146
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:param_set_kgdboc_var
  - drivers/tty/serial/kgdboc.c:param_set_kgdboc_var
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff81199406-ffffffff8119941b: kgdb_unregister_io_module.cold (STB_LOCAL)
ffffffff81198300-ffffffff811983d8: kgdb_unregister_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void kgdb_unregister_io_module(struct kgdb_io *old_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:1185
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:param_set_kgdboc_var
  - drivers/tty/serial/kgdboc.c:param_set_kgdboc_var
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff81be4b5b-ffffffff81be4b70: kgdb_unregister_io_module.cold (STB_LOCAL)
ffffffff81195790-ffffffff81195868: kgdb_unregister_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void kgdb_unregister_io_module(struct kgdb_io *old_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:1159
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:param_set_kgdboc_var
  - drivers/tty/serial/kgdboc.c:param_set_kgdboc_var
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff81bd69ce-ffffffff81bd69e3: kgdb_unregister_io_module.cold (STB_LOCAL)
ffffffff81196730-ffffffff81196808: kgdb_unregister_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void kgdb_unregister_io_module(struct kgdb_io *old_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:1157
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:param_set_kgdboc_var
  - drivers/tty/serial/kgdboc.c:param_set_kgdboc_var
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff81cb39bb-ffffffff81cb39d0: kgdb_unregister_io_module.cold (STB_LOCAL)
ffffffff811bfa30-ffffffff811bfb08: kgdb_unregister_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kgdb_unregister_io_module(struct kgdb_io *old_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81e6481d)
Location: kernel/debug/debug_core.c:1181
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:param_set_kgdboc_var
  - drivers/tty/serial/kgdboc.c:param_set_kgdboc_var
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff81e6481d-ffffffff81e64840: kgdb_unregister_io_module.cold (STB_LOCAL)
ffffffff811f2c10-ffffffff811f2ce6: kgdb_unregister_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kgdb_unregister_io_module(struct kgdb_io *old_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81239840)
Location: kernel/debug/debug_core.c:1169
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:param_set_kgdboc_var
  - drivers/tty/serial/kgdboc.c:param_set_kgdboc_var
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff81239840-ffffffff81239930: kgdb_unregister_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kgdb_unregister_io_module(struct kgdb_io *old_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81250850)
Location: kernel/debug/debug_core.c:1169
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:param_set_kgdboc_var
  - drivers/tty/serial/kgdboc.c:param_set_kgdboc_var
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff81250850-ffffffff81250940: kgdb_unregister_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kgdb_unregister_io_module(struct kgdb_io *old_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8126a6a0)
Location: kernel/debug/debug_core.c:1172
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:param_set_kgdboc_var
  - drivers/tty/serial/kgdboc.c:param_set_kgdboc_var
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff8126a6a0-ffffffff8126a790: kgdb_unregister_io_module (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void kgdb_unregister_io_module(struct kgdb_io *old_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffff8000101f99a8)
Location: kernel/debug/debug_core.c:1077
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffff8000101f99a8-ffff8000101f9ac4: kgdb_unregister_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kgdb_unregister_io_module(struct kgdb_io *old_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (c04399ec)
Location: kernel/debug/debug_core.c:1077
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
c04399ec-c0439af8: kgdb_unregister_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kgdb_unregister_io_module(struct kgdb_io *old_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (c000000000271090)
Location: kernel/debug/debug_core.c:1077
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
c000000000271090-c00000000027120c: kgdb_unregister_io_module (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void kgdb_unregister_io_module(struct kgdb_io *old_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8117c900)
Location: kernel/debug/debug_core.c:1077
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff8117c900-ffffffff8117c9d3: kgdb_unregister_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void kgdb_unregister_io_module(struct kgdb_io *old_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8116fa80)
Location: kernel/debug/debug_core.c:1077
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff8116fa80-ffffffff8116fb53: kgdb_unregister_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void kgdb_unregister_io_module(struct kgdb_io *old_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8117a6d0)
Location: kernel/debug/debug_core.c:1077
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff8117a6d0-ffffffff8117a7a3: kgdb_unregister_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void kgdb_unregister_io_module(struct kgdb_io *old_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81187f50)
Location: kernel/debug/debug_core.c:1077
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff81187f50-ffffffff81188021: kgdb_unregister_io_module (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
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

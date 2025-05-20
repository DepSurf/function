# Function: <code>__handle_sysrq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __handle_sysrq(int key, bool check_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff814ede60)
Location: drivers/tty/sysrq.c:518
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_sr
  - drivers/tty/sysrq.c:handle_sysrq
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:write_sysrq_trigger
```
**Symbols:**

```
ffffffff814ede60-ffffffff814edf9f: __handle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __handle_sysrq(int key, bool check_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff8153eae0)
Location: drivers/tty/sysrq.c:525
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_sr
  - drivers/tty/sysrq.c:write_sysrq_trigger
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:handle_sysrq
```
**Symbols:**

```
ffffffff8153eae0-ffffffff8153ec27: __handle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __handle_sysrq(int key, bool check_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff8156b130)
Location: drivers/tty/sysrq.c:525
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_sr
  - drivers/tty/sysrq.c:write_sysrq_trigger
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:handle_sysrq
```
**Symbols:**

```
ffffffff8156b130-ffffffff8156b277: __handle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __handle_sysrq(int key, unsigned int from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff8157f760)
Location: drivers/tty/sysrq.c:528
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_sr
  - drivers/tty/sysrq.c:write_sysrq_trigger
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:handle_sysrq
```
**Symbols:**

```
ffffffff8157f760-ffffffff8157f8bc: __handle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __handle_sysrq(int key, unsigned int from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff815e42d0)
Location: drivers/tty/sysrq.c:534
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_sr
  - drivers/tty/sysrq.c:write_sysrq_trigger
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:handle_sysrq
```
**Symbols:**

```
ffffffff815e42d0-ffffffff815e4432: __handle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __handle_sysrq(int key, unsigned int from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:534
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_sr
  - drivers/tty/sysrq.c:write_sysrq_trigger
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:handle_sysrq
```
**Symbols:**

```
ffffffff8161db00-ffffffff8161dc11: __handle_sysrq.cold.9 (STB_LOCAL)
ffffffff8161d550-ffffffff8161d598: __handle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __handle_sysrq(int key, unsigned int from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:527
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_sr
  - drivers/tty/sysrq.c:write_sysrq_trigger
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:handle_sysrq
```
**Symbols:**

```
ffffffff8163ad65-ffffffff8163ae76: __handle_sysrq.cold.9 (STB_LOCAL)
ffffffff8163a7b0-ffffffff8163a7f8: __handle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __handle_sysrq(int key, unsigned int from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:527
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_sr
  - drivers/tty/sysrq.c:write_sysrq_trigger
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:handle_sysrq
```
**Symbols:**

```
ffffffff8166f0d0-ffffffff8166f1f7: __handle_sysrq.cold (STB_LOCAL)
ffffffff8166eb40-ffffffff8166eb91: __handle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __handle_sysrq(int key, bool check_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:526
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_sr
  - drivers/tty/sysrq.c:write_sysrq_trigger
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:handle_sysrq
```
**Symbols:**

```
ffffffff816916d0-ffffffff816917d7: __handle_sysrq.cold (STB_LOCAL)
ffffffff81691150-ffffffff816911a1: __handle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __handle_sysrq(int key, bool check_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:541
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_sr
  - drivers/tty/sysrq.c:write_sysrq_trigger
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:handle_sysrq
```
**Symbols:**

```
ffffffff81743e92-ffffffff81743f99: __handle_sysrq.cold (STB_LOCAL)
ffffffff81743950-ffffffff817439a1: __handle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __handle_sysrq(int key, bool check_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:568
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_sr
  - drivers/tty/sysrq.c:write_sysrq_trigger
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:handle_sysrq
```
**Symbols:**

```
ffffffff81c07790-ffffffff81c078b0: __handle_sysrq.cold (STB_LOCAL)
ffffffff8175f7f0-ffffffff8175f841: __handle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __handle_sysrq(int key, bool check_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:569
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_sr
  - drivers/tty/sysrq.c:write_sysrq_trigger
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:handle_sysrq
```
**Symbols:**

```
ffffffff81bf93fa-ffffffff81bf951a: __handle_sysrq.cold (STB_LOCAL)
ffffffff81743650-ffffffff817436a1: __handle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __handle_sysrq(int key, bool check_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:569
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_sr
  - drivers/tty/sysrq.c:write_sysrq_trigger
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:handle_sysrq
```
**Symbols:**

```
ffffffff81cf8ef2-ffffffff81cf9094: __handle_sysrq.cold (STB_LOCAL)
ffffffff817c41e0-ffffffff817c4264: __handle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __handle_sysrq(int key, bool check_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:572
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_sr
  - drivers/tty/sysrq.c:write_sysrq_trigger
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
**Symbols:**

```
ffffffff81ec105f-ffffffff81ec1217: __handle_sysrq.cold (STB_LOCAL)
ffffffff81900ef0-ffffffff81900f6f: __handle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __handle_sysrq(int key, bool check_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:572
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_sr
  - drivers/tty/sysrq.c:write_sysrq_trigger
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
**Symbols:**

```
ffffffff82095453-ffffffff8209546e: __handle_sysrq.cold (STB_LOCAL)
ffffffff81a5abd0-ffffffff81a5ae4f: __handle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __handle_sysrq(int key, bool check_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:572
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_sr
  - drivers/tty/sysrq.c:write_sysrq_trigger
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
**Symbols:**

```
ffffffff821162a2-ffffffff821162bd: __handle_sysrq.cold (STB_LOCAL)
ffffffff81aa5200-ffffffff81aa547f: __handle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __handle_sysrq(u8 key, bool check_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:571
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_sr
  - drivers/tty/sysrq.c:write_sysrq_trigger
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
**Symbols:**

```
ffffffff821f3fb4-ffffffff821f3fcf: __handle_sysrq.cold (STB_LOCAL)
ffffffff81af7c40-ffffffff81af7ecb: __handle_sysrq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __handle_sysrq(int key, bool check_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffff8000108644f8)
Location: drivers/tty/sysrq.c:526
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_sr
  - drivers/tty/sysrq.c:write_sysrq_trigger
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:handle_sysrq
```
**Symbols:**

```
ffff8000108644f8-ffff800010864674: __handle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __handle_sysrq(int key, bool check_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (c0969f10)
Location: drivers/tty/sysrq.c:526
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_sr
  - drivers/tty/sysrq.c:write_sysrq_trigger
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:handle_sysrq
```
**Symbols:**

```
c0969f10-c096a088: __handle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __handle_sysrq(int key, bool check_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (c0000000009035d0)
Location: drivers/tty/sysrq.c:526
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_sr
  - drivers/tty/sysrq.c:write_sysrq_trigger
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:handle_sysrq
  - drivers/tty/sysrq.c:handle_sysrq
```
**Symbols:**

```
c0000000009035d0-c0000000009037e8: __handle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __handle_sysrq(int key, bool check_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffe00053ad04)
Location: drivers/tty/sysrq.c:526
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:write_sysrq_trigger
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:handle_sysrq
```
**Symbols:**

```
ffffffe00053ad04-ffffffe00053ae7c: __handle_sysrq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void __handle_sysrq(int key, bool check_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:526
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_sr
  - drivers/tty/sysrq.c:write_sysrq_trigger
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:handle_sysrq
```
**Symbols:**

```
ffffffff81657150-ffffffff81657257: __handle_sysrq.cold (STB_LOCAL)
ffffffff81656bd0-ffffffff81656c21: __handle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __handle_sysrq(int key, bool check_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:526
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_sr
  - drivers/tty/sysrq.c:write_sysrq_trigger
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:handle_sysrq
```
**Symbols:**

```
ffffffff816374e0-ffffffff816375e7: __handle_sysrq.cold (STB_LOCAL)
ffffffff81636f60-ffffffff81636fb1: __handle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __handle_sysrq(int key, bool check_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:526
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_sr
  - drivers/tty/sysrq.c:write_sysrq_trigger
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:handle_sysrq
```
**Symbols:**

```
ffffffff81685510-ffffffff81685617: __handle_sysrq.cold (STB_LOCAL)
ffffffff81684f90-ffffffff81684fe1: __handle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __handle_sysrq(int key, bool check_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:526
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_sr
  - drivers/tty/sysrq.c:write_sysrq_trigger
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:handle_sysrq
```
**Symbols:**

```
ffffffff8169fb10-ffffffff8169fc1c: __handle_sysrq.cold (STB_LOCAL)
ffffffff8169f590-ffffffff8169f5e6: __handle_sysrq (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int from</code>
</li>
<li>
<b>Param removed. </b>
<code>bool check_mask</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool check_mask</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int from</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int key</code> ➡️ <code>u8 key</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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

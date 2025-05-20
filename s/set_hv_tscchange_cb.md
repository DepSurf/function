# Function: <code>set_hv_tscchange_cb</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void set_hv_tscchange_cb(void (*cb)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102ac30)
Location: arch/x86/hyperv/hv_init.c:192
Inline: False
```
**Symbols:**

```
ffffffff8102ac30-ffffffff8102acaf: set_hv_tscchange_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void set_hv_tscchange_cb(void (*cb)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102b330)
Location: arch/x86/hyperv/hv_init.c:193
Inline: False
```
**Symbols:**

```
ffffffff8102b330-ffffffff8102b3af: set_hv_tscchange_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void set_hv_tscchange_cb(void (*cb)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/hyperv/hv_init.c:146
Inline: False
```
**Symbols:**

```
ffffffff8102d4c9-ffffffff8102d4da: set_hv_tscchange_cb.cold (STB_LOCAL)
ffffffff8102d060-ffffffff8102d112: set_hv_tscchange_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void set_hv_tscchange_cb(void (*cb)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/hyperv/hv_init.c:160
Inline: False
```
**Symbols:**

```
ffffffff8102ddd9-ffffffff8102ddea: set_hv_tscchange_cb.cold (STB_LOCAL)
ffffffff8102d970-ffffffff8102da22: set_hv_tscchange_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void set_hv_tscchange_cb(void (*cb)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/hyperv/hv_init.c:171
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_resume
```
**Symbols:**

```
ffffffff810301a3-ffffffff810301b4: set_hv_tscchange_cb.cold (STB_LOCAL)
ffffffff8102fbf0-ffffffff8102fc6d: set_hv_tscchange_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void set_hv_tscchange_cb(void (*cb)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/hyperv/hv_init.c:174
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_resume
```
**Symbols:**

```
ffffffff81bd2efb-ffffffff81bd2f0c: set_hv_tscchange_cb.cold (STB_LOCAL)
ffffffff81030820-ffffffff8103089d: set_hv_tscchange_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void set_hv_tscchange_cb(void (*cb)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/hyperv/hv_init.c:166
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_resume
```
**Symbols:**

```
ffffffff81bc5283-ffffffff81bc5294: set_hv_tscchange_cb.cold (STB_LOCAL)
ffffffff810313c0-ffffffff8103143d: set_hv_tscchange_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void set_hv_tscchange_cb(void (*cb)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/hyperv/hv_init.c:145
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_resume
```
**Symbols:**

```
ffffffff81c97dc1-ffffffff81c97dd2: set_hv_tscchange_cb.cold (STB_LOCAL)
ffffffff81036500-ffffffff81036587: set_hv_tscchange_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void set_hv_tscchange_cb(void (*cb)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/hyperv/hv_init.c:177
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_resume
```
**Symbols:**

```
ffffffff81e47202-ffffffff81e47213: set_hv_tscchange_cb.cold (STB_LOCAL)
ffffffff8103c450-ffffffff8103c520: set_hv_tscchange_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void set_hv_tscchange_cb(void (*cb)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81044ff0)
Location: arch/x86/hyperv/hv_init.c:167
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_resume
```
**Symbols:**

```
ffffffff81044ff0-ffffffff810450e8: set_hv_tscchange_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void set_hv_tscchange_cb(void (*cb)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81045130)
Location: arch/x86/hyperv/hv_init.c:170
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_resume
```
**Symbols:**

```
ffffffff81045130-ffffffff81045228: set_hv_tscchange_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void set_hv_tscchange_cb(void (*cb)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8104b710)
Location: arch/x86/hyperv/hv_init.c:188
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_resume
```
**Symbols:**

```
ffffffff8104b710-ffffffff8104b808: set_hv_tscchange_cb (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void set_hv_tscchange_cb(void (*cb)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/hyperv/hv_init.c:160
Inline: False
```
**Symbols:**

```
ffffffff8102df39-ffffffff8102df4a: set_hv_tscchange_cb.cold (STB_LOCAL)
ffffffff8102dad0-ffffffff8102db82: set_hv_tscchange_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void set_hv_tscchange_cb(void (*cb)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/hyperv/hv_init.c:160
Inline: False
```
**Symbols:**

```
ffffffff8101d8fc-ffffffff8101d90d: set_hv_tscchange_cb.cold (STB_LOCAL)
ffffffff8101d4f0-ffffffff8101d5c6: set_hv_tscchange_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void set_hv_tscchange_cb(void (*cb)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/hyperv/hv_init.c:160
Inline: False
```
**Symbols:**

```
ffffffff8102dd99-ffffffff8102ddaa: set_hv_tscchange_cb.cold (STB_LOCAL)
ffffffff8102d930-ffffffff8102d9e2: set_hv_tscchange_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void set_hv_tscchange_cb(void (*cb)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/hyperv/hv_init.c:160
Inline: False
```
**Symbols:**

```
ffffffff8102eb89-ffffffff8102eb9a: set_hv_tscchange_cb.cold (STB_LOCAL)
ffffffff8102e720-ffffffff8102e7d2: set_hv_tscchange_cb (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

# Function: <code>gdbstub_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gdbstub_state(struct kgdb_state *ks, char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/gdbstub.c (ffffffff81131c40)
Location: kernel/debug/gdbstub.c:1081
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_gdb_state_pass
```
**Symbols:**

```
ffffffff81131c40-ffffffff81131d0c: gdbstub_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int gdbstub_state(struct kgdb_state *ks, char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/gdbstub.c (ffffffff81139fb0)
Location: kernel/debug/gdbstub.c:1081
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_gdb_state_pass
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff81139fb0-ffffffff8113a07f: gdbstub_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gdbstub_state(struct kgdb_state *ks, char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/gdbstub.c (ffffffff81143d50)
Location: kernel/debug/gdbstub.c:1081
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_gdb_state_pass
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff81143d50-ffffffff81143e1f: gdbstub_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int gdbstub_state(struct kgdb_state *ks, char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/gdbstub.c (ffffffff81145a30)
Location: kernel/debug/gdbstub.c:1082
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_gdb_state_pass
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff81145a30-ffffffff81145b3f: gdbstub_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int gdbstub_state(struct kgdb_state *ks, char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/gdbstub.c (ffffffff81152340)
Location: kernel/debug/gdbstub.c:1082
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_gdb_state_pass
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff81152340-ffffffff81152455: gdbstub_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int gdbstub_state(struct kgdb_state *ks, char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/gdbstub.c (0)
Location: kernel/debug/gdbstub.c:1082
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_gdb_state_pass
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff8116117b-ffffffff8116119f: gdbstub_state.cold.19 (STB_LOCAL)
ffffffff81160ed0-ffffffff81160fcf: gdbstub_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int gdbstub_state(struct kgdb_state *ks, char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/gdbstub.c (0)
Location: kernel/debug/gdbstub.c:1082
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_gdb_state_pass
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff8116dfab-ffffffff8116dfcf: gdbstub_state.cold.19 (STB_LOCAL)
ffffffff8116dd00-ffffffff8116ddff: gdbstub_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int gdbstub_state(struct kgdb_state *ks, char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/gdbstub.c (0)
Location: kernel/debug/gdbstub.c:1083
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_gdb_state_pass
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff8117add3-ffffffff8117adeb: gdbstub_state.cold (STB_LOCAL)
ffffffff8117ab80-ffffffff8117ac45: gdbstub_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int gdbstub_state(struct kgdb_state *ks, char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/gdbstub.c (0)
Location: kernel/debug/gdbstub.c:1083
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_gdb_state_pass
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff81186c63-ffffffff81186c7b: gdbstub_state.cold (STB_LOCAL)
ffffffff81186a10-ffffffff81186ad5: gdbstub_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int gdbstub_state(struct kgdb_state *ks, char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/gdbstub.c (0)
Location: kernel/debug/gdbstub.c:1096
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_gdb_state_pass
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff8119b123-ffffffff8119b13b: gdbstub_state.cold (STB_LOCAL)
ffffffff8119aed0-ffffffff8119af95: gdbstub_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int gdbstub_state(struct kgdb_state *ks, char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/gdbstub.c (0)
Location: kernel/debug/gdbstub.c:1095
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_gdb_state_pass
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff81be4cf9-ffffffff81be4d1d: gdbstub_state.cold (STB_LOCAL)
ffffffff81198040-ffffffff8119818e: gdbstub_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int gdbstub_state(struct kgdb_state *ks, char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/gdbstub.c (0)
Location: kernel/debug/gdbstub.c:1095
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_gdb_state_pass
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff81bd6b6d-ffffffff81bd6b91: gdbstub_state.cold (STB_LOCAL)
ffffffff81198e90-ffffffff81198fde: gdbstub_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gdbstub_state(struct kgdb_state *ks, char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/gdbstub.c (0)
Location: kernel/debug/gdbstub.c:1092
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_gdb_state_pass
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff81cb3ba3-ffffffff81cb3bc7: gdbstub_state.cold (STB_LOCAL)
ffffffff811c2c60-ffffffff811c2dae: gdbstub_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int gdbstub_state(struct kgdb_state *ks, char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/gdbstub.c (0)
Location: kernel/debug/gdbstub.c:1092
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_gdb_state_pass
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff81e64a4d-ffffffff81e64a71: gdbstub_state.cold (STB_LOCAL)
ffffffff811f6430-ffffffff811f6590: gdbstub_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gdbstub_state(struct kgdb_state *ks, char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/gdbstub.c (ffffffff8123d620)
Location: kernel/debug/gdbstub.c:1092
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_gdb_state_pass
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff8123d620-ffffffff8123d79c: gdbstub_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gdbstub_state(struct kgdb_state *ks, char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/gdbstub.c (ffffffff81254650)
Location: kernel/debug/gdbstub.c:1092
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_gdb_state_pass
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff81254650-ffffffff812547c0: gdbstub_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gdbstub_state(struct kgdb_state *ks, char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/gdbstub.c (ffffffff8126e4c0)
Location: kernel/debug/gdbstub.c:1092
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_gdb_state_pass
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff8126e4c0-ffffffff8126e630: gdbstub_state (STB_GLOBAL)
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
int gdbstub_state(struct kgdb_state *ks, char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/gdbstub.c (ffff8000101fca70)
Location: kernel/debug/gdbstub.c:1083
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_gdb_state_pass
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffff8000101fca70-ffff8000101fcbac: gdbstub_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gdbstub_state(struct kgdb_state *ks, char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/gdbstub.c (c043caa8)
Location: kernel/debug/gdbstub.c:1083
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_gdb_state_pass
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
c043caa8-c043cbc0: gdbstub_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gdbstub_state(struct kgdb_state *ks, char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/gdbstub.c (c000000000274f90)
Location: kernel/debug/gdbstub.c:1083
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_gdb_state_pass
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
c000000000274f90-c00000000027512c: gdbstub_state (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int gdbstub_state(struct kgdb_state *ks, char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/gdbstub.c (0)
Location: kernel/debug/gdbstub.c:1083
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_gdb_state_pass
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff8117f283-ffffffff8117f29b: gdbstub_state.cold (STB_LOCAL)
ffffffff8117f030-ffffffff8117f0f5: gdbstub_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int gdbstub_state(struct kgdb_state *ks, char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/gdbstub.c (0)
Location: kernel/debug/gdbstub.c:1083
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_gdb_state_pass
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff811723d3-ffffffff811723eb: gdbstub_state.cold (STB_LOCAL)
ffffffff81172180-ffffffff81172245: gdbstub_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int gdbstub_state(struct kgdb_state *ks, char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/gdbstub.c (0)
Location: kernel/debug/gdbstub.c:1083
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_gdb_state_pass
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff8117d053-ffffffff8117d06b: gdbstub_state.cold (STB_LOCAL)
ffffffff8117ce00-ffffffff8117cec5: gdbstub_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int gdbstub_state(struct kgdb_state *ks, char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/gdbstub.c (0)
Location: kernel/debug/gdbstub.c:1083
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_gdb_state_pass
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff8118a973-ffffffff8118a98b: gdbstub_state.cold (STB_LOCAL)
ffffffff8118a720-ffffffff8118a7e5: gdbstub_state (STB_GLOBAL)
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

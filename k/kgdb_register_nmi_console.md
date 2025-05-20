# Function: <code>kgdb_register_nmi_console</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kgdb_register_nmi_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81510310)
Location: drivers/tty/serial/kgdb_nmi.c:329
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff81510310-ffffffff8151045e: kgdb_register_nmi_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kgdb_register_nmi_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81562880)
Location: drivers/tty/serial/kgdb_nmi.c:329
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff81562880-ffffffff815629c5: kgdb_register_nmi_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kgdb_register_nmi_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8158eff0)
Location: drivers/tty/serial/kgdb_nmi.c:329
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff8158eff0-ffffffff8158f135: kgdb_register_nmi_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int kgdb_register_nmi_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdb_nmi.c (ffffffff815a3110)
Location: drivers/tty/serial/kgdb_nmi.c:329
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff815a3110-ffffffff815a324a: kgdb_register_nmi_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int kgdb_register_nmi_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81608840)
Location: drivers/tty/serial/kgdb_nmi.c:326
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff81608840-ffffffff8160897a: kgdb_register_nmi_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kgdb_register_nmi_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: drivers/tty/serial/kgdb_nmi.c:326
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff81642420-ffffffff81642446: kgdb_register_nmi_console.cold.8 (STB_LOCAL)
ffffffff81641f50-ffffffff8164206b: kgdb_register_nmi_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kgdb_register_nmi_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdb_nmi.c (ffffffff816600ca)
Location: drivers/tty/serial/kgdb_nmi.c:326
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff81660587-ffffffff816605ad: kgdb_register_nmi_console.cold.8 (STB_LOCAL)
ffffffff816600b0-ffffffff816601cb: kgdb_register_nmi_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kgdb_register_nmi_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81695c5c)
Location: drivers/tty/serial/kgdb_nmi.c:326
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff81696128-ffffffff8169614e: kgdb_register_nmi_console.cold (STB_LOCAL)
ffffffff81695c40-ffffffff81695d62: kgdb_register_nmi_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kgdb_register_nmi_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdb_nmi.c (ffffffff816b87ec)
Location: drivers/tty/serial/kgdb_nmi.c:326
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff816b8cb8-ffffffff816b8cde: kgdb_register_nmi_console.cold (STB_LOCAL)
ffffffff816b87d0-ffffffff816b88f2: kgdb_register_nmi_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kgdb_register_nmi_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8176cbb0)
Location: drivers/tty/serial/kgdb_nmi.c:326
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff8176ca90-ffffffff8176cba3: kgdb_register_nmi_console.part.0 (STB_LOCAL)
ffffffff8176cde7-ffffffff8176ce0d: kgdb_register_nmi_console.part.0.cold (STB_LOCAL)
ffffffff8176cbb0-ffffffff8176cbcd: kgdb_register_nmi_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kgdb_register_nmi_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81787670)
Location: drivers/tty/serial/kgdb_nmi.c:326
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff81787550-ffffffff81787663: kgdb_register_nmi_console.part.0 (STB_LOCAL)
ffffffff81c08320-ffffffff81c08346: kgdb_register_nmi_console.part.0.cold (STB_LOCAL)
ffffffff81787670-ffffffff8178768d: kgdb_register_nmi_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kgdb_register_nmi_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8176aeec)
Location: drivers/tty/serial/kgdb_nmi.c:326
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff81bf9ee4-ffffffff81bf9f0a: kgdb_register_nmi_console.cold (STB_LOCAL)
ffffffff8176aed0-ffffffff8176aff4: kgdb_register_nmi_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kgdb_register_nmi_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdb_nmi.c (ffffffff817f054c)
Location: drivers/tty/serial/kgdb_nmi.c:326
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff81cfa74d-ffffffff81cfa792: kgdb_register_nmi_console.cold (STB_LOCAL)
ffffffff817f0530-ffffffff817f0618: kgdb_register_nmi_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int kgdb_register_nmi_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: drivers/tty/serial/kgdb_nmi.c:326
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff81ec29b1-ffffffff81ec29f5: kgdb_register_nmi_console.cold (STB_LOCAL)
ffffffff819308f0-ffffffff819309e0: kgdb_register_nmi_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kgdb_register_nmi_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81a8ee20)
Location: drivers/tty/serial/kgdb_nmi.c:326
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff81a8ee20-ffffffff81a8ef5c: kgdb_register_nmi_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kgdb_register_nmi_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81ada5d0)
Location: drivers/tty/serial/kgdb_nmi.c:326
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff81ada5d0-ffffffff81ada70c: kgdb_register_nmi_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kgdb_register_nmi_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81b2d8d0)
Location: drivers/tty/serial/kgdb_nmi.c:327
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff81b2d8d0-ffffffff81b2da0c: kgdb_register_nmi_console (STB_GLOBAL)
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
int kgdb_register_nmi_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdb_nmi.c (ffff8000108a82b8)
Location: drivers/tty/serial/kgdb_nmi.c:326
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffff8000108a82b8-ffff8000108a8400: kgdb_register_nmi_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int kgdb_register_nmi_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdb_nmi.c (c09a4e20)
Location: drivers/tty/serial/kgdb_nmi.c:326
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
c09a4e20-c09a4f60: kgdb_register_nmi_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int kgdb_register_nmi_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdb_nmi.c (c00000000093f070)
Location: drivers/tty/serial/kgdb_nmi.c:326
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
c00000000093f070-c00000000093f244: kgdb_register_nmi_console (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kgdb_register_nmi_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8167e24c)
Location: drivers/tty/serial/kgdb_nmi.c:326
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff8167e718-ffffffff8167e73e: kgdb_register_nmi_console.cold (STB_LOCAL)
ffffffff8167e230-ffffffff8167e352: kgdb_register_nmi_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kgdb_register_nmi_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8165d33c)
Location: drivers/tty/serial/kgdb_nmi.c:326
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff8165d808-ffffffff8165d82e: kgdb_register_nmi_console.cold (STB_LOCAL)
ffffffff8165d320-ffffffff8165d442: kgdb_register_nmi_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kgdb_register_nmi_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdb_nmi.c (ffffffff816ac62c)
Location: drivers/tty/serial/kgdb_nmi.c:326
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff816acaf8-ffffffff816acb1e: kgdb_register_nmi_console.cold (STB_LOCAL)
ffffffff816ac610-ffffffff816ac732: kgdb_register_nmi_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kgdb_register_nmi_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdb_nmi.c (ffffffff816c6a8c)
Location: drivers/tty/serial/kgdb_nmi.c:326
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff816c6f58-ffffffff816c6f7e: kgdb_register_nmi_console.cold (STB_LOCAL)
ffffffff816c6a70-ffffffff816c6b92: kgdb_register_nmi_console (STB_GLOBAL)
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

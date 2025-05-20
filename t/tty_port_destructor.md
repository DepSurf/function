# Function: <code>tty_port_destructor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tty_port_destructor(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff814eb270)
Location: drivers/tty/tty_port.c:138
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_put
```
**Symbols:**

```
ffffffff814eb270-ffffffff814eb2ef: tty_port_destructor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tty_port_destructor(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8153c0f0)
Location: drivers/tty/tty_port.c:138
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_put
```
**Symbols:**

```
ffffffff8153c0f0-ffffffff8153c16f: tty_port_destructor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tty_port_destructor(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81568750)
Location: drivers/tty/tty_port.c:138
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_put
```
**Symbols:**

```
ffffffff81568750-ffffffff815687cf: tty_port_destructor (STB_LOCAL)
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
In drivers/tty/tty_port.c (ffffffff8157bea5)
Location: drivers/tty/tty_port.c:251
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_put
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tty_port_destructor(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff815e08d0)
Location: drivers/tty/tty_port.c:252
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_put
```
**Symbols:**

```
ffffffff815e08d0-ffffffff815e0943: tty_port_destructor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tty_port_destructor(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81619b70)
Location: drivers/tty/tty_port.c:252
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_put
```
**Symbols:**

```
ffffffff81619b70-ffffffff81619be0: tty_port_destructor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tty_port_destructor(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81636de0)
Location: drivers/tty/tty_port.c:252
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_put
```
**Symbols:**

```
ffffffff81636de0-ffffffff81636e50: tty_port_destructor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void tty_port_destructor(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_port.c (0)
Location: drivers/tty/tty_port.c:252
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_put
```
**Symbols:**

```
ffffffff8166b070-ffffffff8166b0e0: tty_port_destructor (STB_LOCAL)
ffffffff8166b950-ffffffff8166b963: tty_port_destructor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tty_port_destructor(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8168d710)
Location: drivers/tty/tty_port.c:253
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_put
```
**Symbols:**

```
ffffffff8168d710-ffffffff8168d77f: tty_port_destructor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tty_port_destructor(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8173f600)
Location: drivers/tty/tty_port.c:253
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_put
```
**Symbols:**

```
ffffffff8173f600-ffffffff8173f66f: tty_port_destructor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tty_port_destructor(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8175b530)
Location: drivers/tty/tty_port.c:253
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_put
```
**Symbols:**

```
ffffffff8175b530-ffffffff8175b59f: tty_port_destructor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tty_port_destructor(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8173f3d0)
Location: drivers/tty/tty_port.c:254
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_put
```
**Symbols:**

```
ffffffff8173f3d0-ffffffff8173f43f: tty_port_destructor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tty_port_destructor(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff817bfc20)
Location: drivers/tty/tty_port.c:254
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_put
```
**Symbols:**

```
ffffffff817bfc20-ffffffff817bfc8f: tty_port_destructor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tty_port_destructor(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff818fc300)
Location: drivers/tty/tty_port.c:265
Inline: False
```
**Symbols:**

```
ffffffff818fc300-ffffffff818fc388: tty_port_destructor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tty_port_destructor(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81a558f0)
Location: drivers/tty/tty_port.c:286
Inline: False
```
**Symbols:**

```
ffffffff81a558f0-ffffffff81a55978: tty_port_destructor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tty_port_destructor(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81a9fed0)
Location: drivers/tty/tty_port.c:286
Inline: False
```
**Symbols:**

```
ffffffff81a9fed0-ffffffff81a9ff58: tty_port_destructor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tty_port_destructor(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81af2920)
Location: drivers/tty/tty_port.c:286
Inline: False
```
**Symbols:**

```
ffffffff81af2920-ffffffff81af29a8: tty_port_destructor (STB_LOCAL)
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
In drivers/tty/tty_port.c (ffff80001085e1e8)
Location: drivers/tty/tty_port.c:253
Inline: True
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
In drivers/tty/tty_port.c (c096636c)
Location: drivers/tty/tty_port.c:253
Inline: True
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
In drivers/tty/tty_port.c (c0000000008fd980)
Location: drivers/tty/tty_port.c:253
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_put
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
In drivers/tty/tty_port.c (ffffffe000536eda)
Location: drivers/tty/tty_port.c:253
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_put
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void tty_port_destructor(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81653190)
Location: drivers/tty/tty_port.c:253
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_put
```
**Symbols:**

```
ffffffff81653190-ffffffff816531ff: tty_port_destructor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tty_port_destructor(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81633580)
Location: drivers/tty/tty_port.c:253
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_put
```
**Symbols:**

```
ffffffff81633580-ffffffff816335ef: tty_port_destructor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tty_port_destructor(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81681550)
Location: drivers/tty/tty_port.c:253
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_put
```
**Symbols:**

```
ffffffff81681550-ffffffff816815bf: tty_port_destructor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tty_port_destructor(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8169bba0)
Location: drivers/tty/tty_port.c:253
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_put
```
**Symbols:**

```
ffffffff8169bba0-ffffffff8169bc0f: tty_port_destructor (STB_LOCAL)
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

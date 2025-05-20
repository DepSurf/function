# Function: <code>_proc_do_string</code>

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
In kernel/sysctl.c (ffffffff81087d38)
Location: kernel/sysctl.c:1812
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dostring
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
In kernel/sysctl.c (ffffffff8108abb8)
Location: kernel/sysctl.c:1932
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dostring
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
In kernel/sysctl.c (ffffffff8108fb08)
Location: kernel/sysctl.c:1917
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dostring
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
In kernel/sysctl.c (ffffffff8108cbe5)
Location: kernel/sysctl.c:1915
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dostring
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
In kernel/sysctl.c (ffffffff81093855)
Location: kernel/sysctl.c:1907
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dostring
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
In kernel/sysctl.c (ffffffff810972af)
Location: kernel/sysctl.c:1912
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dostring
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
In kernel/sysctl.c (ffffffff8109f62f)
Location: kernel/sysctl.c:1960
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dostring
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
In kernel/sysctl.c (ffffffff810a3d00)
Location: kernel/sysctl.c:2010
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dostring
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
In kernel/sysctl.c (ffffffff810aa2d0)
Location: kernel/sysctl.c:2012
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dostring
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int _proc_do_string(char *data, int maxlen, int write, char *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810b1c30)
Location: kernel/sysctl.c:246
Inline: False
```
**Symbols:**

```
ffffffff810b1c30-ffffffff810b1d7e: _proc_do_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int _proc_do_string(char *data, int maxlen, int write, char *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810ad460)
Location: kernel/sysctl.c:245
Inline: False
```
**Symbols:**

```
ffffffff810ad460-ffffffff810ad5ae: _proc_do_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int _proc_do_string(char *data, int maxlen, int write, char *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810ae660)
Location: kernel/sysctl.c:257
Inline: False
```
**Symbols:**

```
ffffffff810ae660-ffffffff810ae7bc: _proc_do_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int _proc_do_string(char *data, int maxlen, int write, char *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810c01e0)
Location: kernel/sysctl.c:266
Inline: False
```
**Symbols:**

```
ffffffff810c01e0-ffffffff810c033c: _proc_do_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int _proc_do_string(char *data, int maxlen, int write, char *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810d77d0)
Location: kernel/sysctl.c:146
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_dostring
```
**Symbols:**

```
ffffffff810d77d0-ffffffff810d7948: _proc_do_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int _proc_do_string(char *data, int maxlen, int write, char *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810f7430)
Location: kernel/sysctl.c:148
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_dostring
```
**Symbols:**

```
ffffffff810f7430-ffffffff810f75a8: _proc_do_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int _proc_do_string(char *data, int maxlen, int write, char *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81103830)
Location: kernel/sysctl.c:147
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_dostring
```
**Symbols:**

```
ffffffff81103830-ffffffff811039a8: _proc_do_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int _proc_do_string(char *data, int maxlen, int write, char *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8110d180)
Location: kernel/sysctl.c:147
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_dostring
```
**Symbols:**

```
ffffffff8110d180-ffffffff8110d2f8: _proc_do_string (STB_LOCAL)
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
int _proc_do_string(char *data, int maxlen, int write, char *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffff800010104760)
Location: kernel/sysctl.c:2012
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_dostring
```
**Symbols:**

```
ffff800010104760-ffff800010104d00: _proc_do_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int _proc_do_string(char *data, int maxlen, int write, char *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (c035e358)
Location: kernel/sysctl.c:2012
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_dostring
```
**Symbols:**

```
c035e358-c035e648: _proc_do_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int _proc_do_string(char *data, int maxlen, int write, char *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (c00000000014a410)
Location: kernel/sysctl.c:2012
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_dostring
```
**Symbols:**

```
c00000000014a410-c00000000014a804: _proc_do_string (STB_LOCAL)
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
In kernel/sysctl.c (ffffffe0000c9344)
Location: kernel/sysctl.c:2012
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dostring
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
In kernel/sysctl.c (ffffffff810a3bf0)
Location: kernel/sysctl.c:2012
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dostring
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
In kernel/sysctl.c (ffffffff810925d0)
Location: kernel/sysctl.c:2012
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dostring
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
In kernel/sysctl.c (ffffffff810a3ba0)
Location: kernel/sysctl.c:2012
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dostring
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
In kernel/sysctl.c (ffffffff810abc60)
Location: kernel/sysctl.c:2012
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dostring
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
<b>Arch</b>
<ul>
</ul>

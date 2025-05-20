# Function: <code>kgdboc_option_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kgdboc_option_setup(char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdboc.c (ffffffff815108f0)
Location: drivers/tty/serial/kgdboc.c:134
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
  - drivers/tty/serial/kgdboc.c:kgdboc_early_init
```
**Symbols:**

```
ffffffff815108f0-ffffffff81510992: kgdboc_option_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kgdboc_option_setup(char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdboc.c (ffffffff81562e80)
Location: drivers/tty/serial/kgdboc.c:134
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_early_init
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff81562e80-ffffffff81562f1f: kgdboc_option_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kgdboc_option_setup(char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdboc.c (ffffffff8158f5f0)
Location: drivers/tty/serial/kgdboc.c:134
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_early_init
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff8158f5f0-ffffffff8158f68f: kgdboc_option_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kgdboc_option_setup(char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdboc.c (ffffffff815a36a0)
Location: drivers/tty/serial/kgdboc.c:134
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_early_init
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff815a36a0-ffffffff815a373f: kgdboc_option_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kgdboc_option_setup(char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdboc.c (ffffffff81608de0)
Location: drivers/tty/serial/kgdboc.c:131
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_early_init
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff81608de0-ffffffff81608e7f: kgdboc_option_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int kgdboc_option_setup(char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdboc.c (0)
Location: drivers/tty/serial/kgdboc.c:131
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_early_init
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff816424f0-ffffffff81642583: kgdboc_option_setup (STB_LOCAL)
ffffffff81642a7f-ffffffff81642a95: kgdboc_option_setup.cold.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int kgdboc_option_setup(char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdboc.c (0)
Location: drivers/tty/serial/kgdboc.c:303
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_early_init
```
**Symbols:**

```
ffffffff81660660-ffffffff816606fc: kgdboc_option_setup (STB_LOCAL)
ffffffff81660c6b-ffffffff81660c97: kgdboc_option_setup.cold.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int kgdboc_option_setup(char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdboc.c (0)
Location: drivers/tty/serial/kgdboc.c:307
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_early_init
```
**Symbols:**

```
ffffffff81696200-ffffffff8169629c: kgdboc_option_setup (STB_LOCAL)
ffffffff8169682e-ffffffff8169685a: kgdboc_option_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int kgdboc_option_setup(char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdboc.c (0)
Location: drivers/tty/serial/kgdboc.c:307
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_early_init
```
**Symbols:**

```
ffffffff816b8d90-ffffffff816b8e2c: kgdboc_option_setup (STB_LOCAL)
ffffffff816b93be-ffffffff816b93ea: kgdboc_option_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int kgdboc_option_setup(char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdboc.c (0)
Location: drivers/tty/serial/kgdboc.c:402
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_early_init
```
**Symbols:**

```
ffffffff8176cfc0-ffffffff8176d05f: kgdboc_option_setup (STB_LOCAL)
ffffffff8176d626-ffffffff8176d652: kgdboc_option_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int kgdboc_option_setup(char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdboc.c (0)
Location: drivers/tty/serial/kgdboc.c:402
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_early_init
```
**Symbols:**

```
ffffffff81787a20-ffffffff81787abf: kgdboc_option_setup (STB_LOCAL)
ffffffff81c08370-ffffffff81c0839c: kgdboc_option_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int kgdboc_option_setup(char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdboc.c (0)
Location: drivers/tty/serial/kgdboc.c:402
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_early_init
```
**Symbols:**

```
ffffffff8176b370-ffffffff8176b40f: kgdboc_option_setup (STB_LOCAL)
ffffffff81bf9f34-ffffffff81bf9f60: kgdboc_option_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int kgdboc_option_setup(char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdboc.c (0)
Location: drivers/tty/serial/kgdboc.c:402
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_early_init
```
**Symbols:**

```
ffffffff817f0a00-ffffffff817f0a9f: kgdboc_option_setup (STB_LOCAL)
ffffffff81cfa7bc-ffffffff81cfa7e8: kgdboc_option_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int kgdboc_option_setup(char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdboc.c (0)
Location: drivers/tty/serial/kgdboc.c:402
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_early_init
```
**Symbols:**

```
ffffffff81930e90-ffffffff81930f56: kgdboc_option_setup (STB_LOCAL)
ffffffff81ec2a1f-ffffffff81ec2a41: kgdboc_option_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kgdboc_option_setup(char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdboc.c (ffffffff81a8f520)
Location: drivers/tty/serial/kgdboc.c:414
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_early_init
```
**Symbols:**

```
ffffffff81a8f520-ffffffff81a8f621: kgdboc_option_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kgdboc_option_setup(char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdboc.c (ffffffff81adacf0)
Location: drivers/tty/serial/kgdboc.c:414
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_early_init
```
**Symbols:**

```
ffffffff81adacf0-ffffffff81adadf1: kgdboc_option_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kgdboc_option_setup(char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdboc.c (ffffffff81b2e050)
Location: drivers/tty/serial/kgdboc.c:414
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_early_init
```
**Symbols:**

```
ffffffff81b2e050-ffffffff81b2e151: kgdboc_option_setup (STB_LOCAL)
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
int kgdboc_option_setup(char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdboc.c (ffff8000108a8940)
Location: drivers/tty/serial/kgdboc.c:307
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_early_init
```
**Symbols:**

```
ffff8000108a8940-ffff8000108a89bc: kgdboc_option_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kgdboc_option_setup(char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdboc.c (c09a533c)
Location: drivers/tty/serial/kgdboc.c:307
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_early_init
```
**Symbols:**

```
c09a533c-c09a53a8: kgdboc_option_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kgdboc_option_setup(char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdboc.c (c00000000093f9a0)
Location: drivers/tty/serial/kgdboc.c:307
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_early_init
```
**Symbols:**

```
c00000000093f9a0-c00000000093fa34: kgdboc_option_setup (STB_LOCAL)
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
int kgdboc_option_setup(char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdboc.c (0)
Location: drivers/tty/serial/kgdboc.c:307
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_early_init
```
**Symbols:**

```
ffffffff8167e7f0-ffffffff8167e88c: kgdboc_option_setup (STB_LOCAL)
ffffffff8167ee1e-ffffffff8167ee4a: kgdboc_option_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int kgdboc_option_setup(char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdboc.c (0)
Location: drivers/tty/serial/kgdboc.c:307
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_early_init
```
**Symbols:**

```
ffffffff8165d8e0-ffffffff8165d97c: kgdboc_option_setup (STB_LOCAL)
ffffffff8165df0e-ffffffff8165df3a: kgdboc_option_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int kgdboc_option_setup(char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdboc.c (0)
Location: drivers/tty/serial/kgdboc.c:307
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_early_init
```
**Symbols:**

```
ffffffff816acbd0-ffffffff816acc6c: kgdboc_option_setup (STB_LOCAL)
ffffffff816ad1fe-ffffffff816ad22a: kgdboc_option_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int kgdboc_option_setup(char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdboc.c (0)
Location: drivers/tty/serial/kgdboc.c:307
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_early_init
```
**Symbols:**

```
ffffffff816c7030-ffffffff816c70cc: kgdboc_option_setup (STB_LOCAL)
ffffffff816c765e-ffffffff816c768a: kgdboc_option_setup.cold (STB_LOCAL)
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

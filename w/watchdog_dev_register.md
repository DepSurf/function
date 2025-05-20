# Function: <code>watchdog_dev_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int watchdog_dev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8168b5c0)
Location: drivers/watchdog/watchdog_dev.c:526
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffffffff8168b5c0-ffffffff8168b6ea: watchdog_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int watchdog_dev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff816ecad0)
Location: drivers/watchdog/watchdog_dev.c:920
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffffffff816ecad0-ffffffff816ecdb8: watchdog_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int watchdog_dev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8171db70)
Location: drivers/watchdog/watchdog_dev.c:1010
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffffffff8171db70-ffffffff8171de98: watchdog_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int watchdog_dev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81735da0)
Location: drivers/watchdog/watchdog_dev.c:1028
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffffffff81735da0-ffffffff8173609c: watchdog_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int watchdog_dev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff817a7b20)
Location: drivers/watchdog/watchdog_dev.c:1049
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffffffff817a7b20-ffffffff817a7e5f: watchdog_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int watchdog_dev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:1072
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffffffff817ef817-ffffffff817ef8e5: watchdog_dev_register.cold.11 (STB_LOCAL)
ffffffff817ef560-ffffffff817ef7e2: watchdog_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int watchdog_dev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:1072
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffffffff8181b6e9-ffffffff8181b7dd: watchdog_dev_register.cold.11 (STB_LOCAL)
ffffffff8181b430-ffffffff8181b6b4: watchdog_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int watchdog_dev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:1099
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffffffff8185d976-ffffffff8185da42: watchdog_dev_register.cold (STB_LOCAL)
ffffffff8185d670-ffffffff8185d943: watchdog_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int watchdog_dev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8188f430)
Location: drivers/watchdog/watchdog_dev.c:1088
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffffffff8188f430-ffffffff8188f475: watchdog_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int watchdog_dev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8195e0d0)
Location: drivers/watchdog/watchdog_dev.c:1109
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffffffff8195e0d0-ffffffff8195e111: watchdog_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int watchdog_dev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81964ad0)
Location: drivers/watchdog/watchdog_dev.c:1112
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffffffff81964ad0-ffffffff81964b11: watchdog_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int watchdog_dev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81948ef0)
Location: drivers/watchdog/watchdog_dev.c:1112
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffffffff81948ef0-ffffffff81948f31: watchdog_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int watchdog_dev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff819edef0)
Location: drivers/watchdog/watchdog_dev.c:1121
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffffffff819edef0-ffffffff819edf31: watchdog_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int watchdog_dev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81b54840)
Location: drivers/watchdog/watchdog_dev.c:1126
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffffffff81b54840-ffffffff81b5488c: watchdog_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int watchdog_dev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81ced5b0)
Location: drivers/watchdog/watchdog_dev.c:1138
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffffffff81ced5b0-ffffffff81ced5fc: watchdog_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int watchdog_dev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81d562f0)
Location: drivers/watchdog/watchdog_dev.c:1159
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffffffff81d562f0-ffffffff81d5633c: watchdog_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int watchdog_dev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0d200)
Location: drivers/watchdog/watchdog_dev.c:1158
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffffffff81e0d200-ffffffff81e0d24c: watchdog_dev_register (STB_GLOBAL)
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
int watchdog_dev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffff800010ae0a40)
Location: drivers/watchdog/watchdog_dev.c:1088
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffff800010ae0a40-ffff800010ae0d24: watchdog_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int watchdog_dev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (c0bc1df8)
Location: drivers/watchdog/watchdog_dev.c:1088
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
c0bc1df8-c0bc1e44: watchdog_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int watchdog_dev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (c000000000bc89c0)
Location: drivers/watchdog/watchdog_dev.c:1088
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
c000000000bc89c0-c000000000bc8a48: watchdog_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int watchdog_dev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffe0006d7d62)
Location: drivers/watchdog/watchdog_dev.c:1088
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffffffe0006d7d62-ffffffe0006d8044: watchdog_dev_register (STB_GLOBAL)
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
int watchdog_dev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff818352b0)
Location: drivers/watchdog/watchdog_dev.c:1088
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffffffff818352b0-ffffffff818352f5: watchdog_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int watchdog_dev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff817fc940)
Location: drivers/watchdog/watchdog_dev.c:1088
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffffffff817fc940-ffffffff817fc985: watchdog_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int watchdog_dev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff818848e0)
Location: drivers/watchdog/watchdog_dev.c:1088
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffffffff818848e0-ffffffff81884925: watchdog_dev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int watchdog_dev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff818a03a0)
Location: drivers/watchdog/watchdog_dev.c:1088
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffffffff818a03a0-ffffffff818a03e5: watchdog_dev_register (STB_GLOBAL)
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

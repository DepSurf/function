# Function: <code>ps2_begin_command</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ps2_begin_command(struct ps2dev *ps2dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81665e30)
Location: drivers/input/serio/libps2.c:57
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_command
```
**Symbols:**

```
ffffffff81665e30-ffffffff81665e5a: ps2_begin_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ps2_begin_command(struct ps2dev *ps2dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff816c6b03)
Location: drivers/input/serio/libps2.c:57
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
```
**Symbols:**

```
ffffffff816c60b0-ffffffff816c60d8: ps2_begin_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ps2_begin_command(struct ps2dev *ps2dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff816f4b03)
Location: drivers/input/serio/libps2.c:57
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
```
**Symbols:**

```
ffffffff816f40d0-ffffffff816f40f8: ps2_begin_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ps2_begin_command(struct ps2dev *ps2dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff8170a673)
Location: drivers/input/serio/libps2.c:57
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
```
**Symbols:**

```
ffffffff81709c30-ffffffff81709c58: ps2_begin_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ps2_begin_command(struct ps2dev *ps2dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff8177b823)
Location: drivers/input/serio/libps2.c:57
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
```
**Symbols:**

```
ffffffff8177ade0-ffffffff8177ae08: ps2_begin_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ps2_begin_command(struct ps2dev *ps2dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff817bc84b)
Location: drivers/input/serio/libps2.c:105
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
```
**Symbols:**

```
ffffffff817bba90-ffffffff817bbab8: ps2_begin_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ps2_begin_command(struct ps2dev *ps2dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff817e3cab)
Location: drivers/input/serio/libps2.c:105
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
```
**Symbols:**

```
ffffffff817e2ef0-ffffffff817e2f18: ps2_begin_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void ps2_begin_command(struct ps2dev *ps2dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff8182466b)
Location: drivers/input/serio/libps2.c:101
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
```
**Symbols:**

```
ffffffff81823870-ffffffff81823898: ps2_begin_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void ps2_begin_command(struct ps2dev *ps2dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81855b3b)
Location: drivers/input/serio/libps2.c:101
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
```
**Symbols:**

```
ffffffff81854d30-ffffffff81854d58: ps2_begin_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void ps2_begin_command(struct ps2dev *ps2dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff8192804c)
Location: drivers/input/serio/libps2.c:101
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
```
**Symbols:**

```
ffffffff81927240-ffffffff81927268: ps2_begin_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ps2_begin_command(struct ps2dev *ps2dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff8192f55c)
Location: drivers/input/serio/libps2.c:101
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
```
**Symbols:**

```
ffffffff8192e760-ffffffff8192e788: ps2_begin_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ps2_begin_command(struct ps2dev *ps2dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff819128dc)
Location: drivers/input/serio/libps2.c:101
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
```
**Symbols:**

```
ffffffff81911b40-ffffffff81911b68: ps2_begin_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void ps2_begin_command(struct ps2dev *ps2dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff819b492c)
Location: drivers/input/serio/libps2.c:101
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
```
**Symbols:**

```
ffffffff819b3ac0-ffffffff819b3ae8: ps2_begin_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void ps2_begin_command(struct ps2dev *ps2dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81b13acc)
Location: drivers/input/serio/libps2.c:101
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
```
**Symbols:**

```
ffffffff81b13030-ffffffff81b13060: ps2_begin_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ps2_begin_command(struct ps2dev *ps2dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81ca4a5c)
Location: drivers/input/serio/libps2.c:102
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
```
**Symbols:**

```
ffffffff81ca3f30-ffffffff81ca3f60: ps2_begin_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ps2_begin_command(struct ps2dev *ps2dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81d0c18c)
Location: drivers/input/serio/libps2.c:129
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
```
**Symbols:**

```
ffffffff81d0b610-ffffffff81d0b640: ps2_begin_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ps2_begin_command(struct ps2dev *ps2dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81dc1e1c)
Location: drivers/input/serio/libps2.c:129
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
```
**Symbols:**

```
ffffffff81dc12a0-ffffffff81dc12d0: ps2_begin_command (STB_GLOBAL)
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
void ps2_begin_command(struct ps2dev *ps2dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffff800010a94988)
Location: drivers/input/serio/libps2.c:101
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
```
**Symbols:**

```
ffff800010a93958-ffff800010a93990: ps2_begin_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ps2_begin_command(struct ps2dev *ps2dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (c0b7744c)
Location: drivers/input/serio/libps2.c:101
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
```
**Symbols:**

```
c0b76be0-c0b76c10: ps2_begin_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void ps2_begin_command(struct ps2dev *ps2dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (c000000000b73824)
Location: drivers/input/serio/libps2.c:101
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
```
**Symbols:**

```
c000000000b723c0-c000000000b7242c: ps2_begin_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ps2_begin_command(struct ps2dev *ps2dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffe0006a68f6)
Location: drivers/input/serio/libps2.c:101
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
```
**Symbols:**

```
ffffffe0006a5bf6-ffffffe0006a5c3c: ps2_begin_command (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void ps2_begin_command(struct ps2dev *ps2dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff8180ab4b)
Location: drivers/input/serio/libps2.c:101
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
```
**Symbols:**

```
ffffffff81809d40-ffffffff81809d68: ps2_begin_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void ps2_begin_command(struct ps2dev *ps2dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff817d22bb)
Location: drivers/input/serio/libps2.c:101
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
```
**Symbols:**

```
ffffffff817d14e0-ffffffff817d1508: ps2_begin_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void ps2_begin_command(struct ps2dev *ps2dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81849ccb)
Location: drivers/input/serio/libps2.c:101
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
```
**Symbols:**

```
ffffffff81848ec0-ffffffff81848ee8: ps2_begin_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void ps2_begin_command(struct ps2dev *ps2dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81864bbb)
Location: drivers/input/serio/libps2.c:101
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
```
**Symbols:**

```
ffffffff81864380-ffffffff818643a8: ps2_begin_command (STB_GLOBAL)
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

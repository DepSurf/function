# Function: <code>mmc_retune_unpause</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_unpause(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81724eaa)
Location: drivers/mmc/core/host.c:85
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
```
**Symbols:**

```
ffffffff81724dd0-ffffffff81724e15: mmc_retune_unpause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_unpause(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81757e2a)
Location: drivers/mmc/core/host.c:85
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
```
**Symbols:**

```
ffffffff81757d50-ffffffff81757d95: mmc_retune_unpause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_unpause(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff817760ea)
Location: drivers/mmc/core/host.c:83
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
```
**Symbols:**

```
ffffffff81776020-ffffffff8177605a: mmc_retune_unpause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_unpause(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff817ec45a)
Location: drivers/mmc/core/host.c:83
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
```
**Symbols:**

```
ffffffff817ec390-ffffffff817ec3ca: mmc_retune_unpause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_unpause(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81835665)
Location: drivers/mmc/core/host.c:83
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
```
**Symbols:**

```
ffffffff818355a0-ffffffff818355d9: mmc_retune_unpause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_unpause(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81861615)
Location: drivers/mmc/core/host.c:83
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/host.c:mmc_retune_disable
```
**Symbols:**

```
ffffffff81861550-ffffffff81861589: mmc_retune_unpause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_retune_unpause(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff818a5345)
Location: drivers/mmc/core/host.c:80
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/host.c:mmc_retune_disable
```
**Symbols:**

```
ffffffff818a5510-ffffffff818a551a: mmc_retune_unpause.cold (STB_LOCAL)
ffffffff818a5280-ffffffff818a52b7: mmc_retune_unpause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_unpause(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff818d77c5)
Location: drivers/mmc/core/host.c:80
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/host.c:mmc_retune_disable
```
**Symbols:**

```
ffffffff818d7700-ffffffff818d7739: mmc_retune_unpause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_unpause(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff819aa125)
Location: drivers/mmc/core/host.c:80
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/host.c:mmc_retune_disable
```
**Symbols:**

```
ffffffff819a9da0-ffffffff819a9dd6: mmc_retune_unpause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_unpause(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff819acd45)
Location: drivers/mmc/core/host.c:82
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/host.c:mmc_retune_disable
```
**Symbols:**

```
ffffffff819acc80-ffffffff819accb4: mmc_retune_unpause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_unpause(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81991585)
Location: drivers/mmc/core/host.c:121
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/host.c:mmc_retune_disable
```
**Symbols:**

```
ffffffff81990df0-ffffffff81990e26: mmc_retune_unpause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_unpause(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81a3cd35)
Location: drivers/mmc/core/host.c:134
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/host.c:mmc_retune_disable
```
**Symbols:**

```
ffffffff81a3c7f0-ffffffff81a3c826: mmc_retune_unpause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_unpause(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81ba9df5)
Location: drivers/mmc/core/host.c:134
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/host.c:mmc_retune_disable
```
**Symbols:**

```
ffffffff81ba9880-ffffffff81ba98c6: mmc_retune_unpause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_unpause(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81d4cc95)
Location: drivers/mmc/core/host.c:134
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/host.c:mmc_retune_disable
```
**Symbols:**

```
ffffffff81d4c620-ffffffff81d4c666: mmc_retune_unpause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_unpause(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81db75f5)
Location: drivers/mmc/core/host.c:134
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/host.c:mmc_retune_disable
```
**Symbols:**

```
ffffffff81db6ef0-ffffffff81db6f36: mmc_retune_unpause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_unpause(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81e6fac5)
Location: drivers/mmc/core/host.c:133
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/host.c:mmc_retune_disable
```
**Symbols:**

```
ffffffff81e6f3c0-ffffffff81e6f406: mmc_retune_unpause (STB_GLOBAL)
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
void mmc_retune_unpause(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffff800010b31b58)
Location: drivers/mmc/core/host.c:80
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/host.c:mmc_retune_disable
```
**Symbols:**

```
ffff800010b31a30-ffff800010b31a84: mmc_retune_unpause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_unpause(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (c0c0c7b0)
Location: drivers/mmc/core/host.c:80
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/host.c:mmc_retune_disable
```
**Symbols:**

```
c0c0c6b8-c0c0c700: mmc_retune_unpause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_unpause(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (c000000000c2b9f0)
Location: drivers/mmc/core/host.c:80
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/host.c:mmc_retune_disable
```
**Symbols:**

```
c000000000c2b880-c000000000c2b8c4: mmc_retune_unpause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_unpause(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffe00070a556)
Location: drivers/mmc/core/host.c:80
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/host.c:mmc_retune_disable
```
**Symbols:**

```
ffffffe00070a436-ffffffe00070a486: mmc_retune_unpause (STB_GLOBAL)
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
void mmc_retune_unpause(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff8187b185)
Location: drivers/mmc/core/host.c:80
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/host.c:mmc_retune_disable
```
**Symbols:**

```
ffffffff8187b0c0-ffffffff8187b0f9: mmc_retune_unpause (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_unpause(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff818cc625)
Location: drivers/mmc/core/host.c:80
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/host.c:mmc_retune_disable
```
**Symbols:**

```
ffffffff818cc560-ffffffff818cc599: mmc_retune_unpause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_unpause(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff818e9145)
Location: drivers/mmc/core/host.c:80
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/host.c:mmc_retune_disable
```
**Symbols:**

```
ffffffff818e9080-ffffffff818e90b9: mmc_retune_unpause (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>

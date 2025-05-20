# Function: <code>do_poweroff</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
void do_poweroff(struct work_struct *dummy);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/poweroff.c (ffffffff810d6550)
Location: kernel/power/poweroff.c:20
Inline: False
```
```
In drivers/xen/manage.c (ffffffff814c75f0)
Location: drivers/xen/manage.c:187
Inline: False
```
**Symbols:**

```
ffffffff810d6550-ffffffff810d6560: do_poweroff (STB_LOCAL)
ffffffff814c75f0-ffffffff814c762b: do_poweroff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
void do_poweroff(struct work_struct *dummy);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/poweroff.c (ffffffff810db3d0)
Location: kernel/power/poweroff.c:20
Inline: False
```
```
In drivers/xen/manage.c (ffffffff81517e80)
Location: drivers/xen/manage.c:187
Inline: False
```
**Symbols:**

```
ffffffff810db3d0-ffffffff810db3e0: do_poweroff (STB_LOCAL)
ffffffff81517e80-ffffffff81517ebb: do_poweroff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
void do_poweroff(struct work_struct *dummy);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/poweroff.c (ffffffff810e1ea0)
Location: kernel/power/poweroff.c:20
Inline: False
```
```
In drivers/xen/manage.c (ffffffff81544170)
Location: drivers/xen/manage.c:189
Inline: False
```
**Symbols:**

```
ffffffff810e1ea0-ffffffff810e1eb0: do_poweroff (STB_LOCAL)
ffffffff81544170-ffffffff815441ab: do_poweroff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
void do_poweroff(struct work_struct *dummy);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/poweroff.c (ffffffff810e0fe0)
Location: kernel/power/poweroff.c:20
Inline: False
```
```
In drivers/xen/manage.c (ffffffff81557ff0)
Location: drivers/xen/manage.c:189
Inline: False
```
**Symbols:**

```
ffffffff810e0fe0-ffffffff810e0ff0: do_poweroff (STB_LOCAL)
ffffffff81557ff0-ffffffff8155802c: do_poweroff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
void do_poweroff(struct work_struct *dummy);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/poweroff.c (ffffffff810e92b0)
Location: kernel/power/poweroff.c:20
Inline: False
```
```
In drivers/xen/manage.c (ffffffff815bc170)
Location: drivers/xen/manage.c:186
Inline: False
```
**Symbols:**

```
ffffffff810e92b0-ffffffff810e92c0: do_poweroff (STB_LOCAL)
ffffffff815bc170-ffffffff815bc1ac: do_poweroff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
void do_poweroff(struct work_struct *dummy);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/poweroff.c (ffffffff810f15e0)
Location: kernel/power/poweroff.c:20
Inline: False
```
```
In drivers/xen/manage.c (ffffffff815f4650)
Location: drivers/xen/manage.c:186
Inline: False
```
**Symbols:**

```
ffffffff810f15e0-ffffffff810f15f0: do_poweroff (STB_LOCAL)
ffffffff815f4650-ffffffff815f468c: do_poweroff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
void do_poweroff(struct work_struct *dummy);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/poweroff.c (ffffffff810fcc70)
Location: kernel/power/poweroff.c:20
Inline: False
```
```
In drivers/xen/manage.c (ffffffff8160f4b0)
Location: drivers/xen/manage.c:186
Inline: False
```
**Symbols:**

```
ffffffff810fcc70-ffffffff810fcc80: do_poweroff (STB_LOCAL)
ffffffff8160f4b0-ffffffff8160f4ec: do_poweroff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Transformation ⚠️</summary>

```c
void do_poweroff(struct work_struct *dummy);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/poweroff.c (ffffffff81105360)
Location: kernel/power/poweroff.c:19
Inline: False
```
```
In drivers/xen/manage.c (0)
Location: drivers/xen/manage.c:187
Inline: False
```
**Symbols:**

```
ffffffff81105360-ffffffff81105370: do_poweroff (STB_LOCAL)
ffffffff816432b0-ffffffff816432e3: do_poweroff (STB_LOCAL)
ffffffff816436ac-ffffffff816436bd: do_poweroff.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Transformation ⚠️</summary>

```c
void do_poweroff(struct work_struct *dummy);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/poweroff.c (ffffffff811116e0)
Location: kernel/power/poweroff.c:19
Inline: False
```
```
In drivers/xen/manage.c (0)
Location: drivers/xen/manage.c:187
Inline: False
```
**Symbols:**

```
ffffffff811116e0-ffffffff811116f0: do_poweroff (STB_LOCAL)
ffffffff81665850-ffffffff81665883: do_poweroff (STB_LOCAL)
ffffffff81665c4c-ffffffff81665c5d: do_poweroff.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Transformation ⚠️</summary>

```c
void do_poweroff(struct work_struct *dummy);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/poweroff.c (ffffffff8111c7b0)
Location: kernel/power/poweroff.c:19
Inline: False
```
```
In drivers/xen/manage.c (0)
Location: drivers/xen/manage.c:187
Inline: False
```
**Symbols:**

```
ffffffff8111c7b0-ffffffff8111c7c0: do_poweroff (STB_LOCAL)
ffffffff81714f10-ffffffff81714f43: do_poweroff (STB_LOCAL)
ffffffff817153ad-ffffffff817153be: do_poweroff.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Transformation ⚠️</summary>

```c
void do_poweroff(struct work_struct *dummy);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/poweroff.c (ffffffff81117110)
Location: kernel/power/poweroff.c:19
Inline: False
```
```
In drivers/xen/manage.c (0)
Location: drivers/xen/manage.c:188
Inline: False
```
**Symbols:**

```
ffffffff81117110-ffffffff81117120: do_poweroff (STB_LOCAL)
ffffffff81731b00-ffffffff81731b33: do_poweroff (STB_LOCAL)
ffffffff81c04e33-ffffffff81c04e44: do_poweroff.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Transformation ⚠️</summary>

```c
void do_poweroff(struct work_struct *dummy);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/poweroff.c (ffffffff81117840)
Location: kernel/power/poweroff.c:19
Inline: False
```
```
In drivers/xen/manage.c (0)
Location: drivers/xen/manage.c:188
Inline: False
```
**Symbols:**

```
ffffffff81117840-ffffffff81117850: do_poweroff (STB_LOCAL)
ffffffff817155f0-ffffffff81715623: do_poweroff (STB_LOCAL)
ffffffff81bf6abd-ffffffff81bf6ace: do_poweroff.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
void do_poweroff(struct work_struct *dummy);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/poweroff.c (ffffffff81137ba0)
Location: kernel/power/poweroff.c:19
Inline: False
```
```
In drivers/xen/manage.c (0)
Location: drivers/xen/manage.c:188
Inline: False
```
**Symbols:**

```
ffffffff81137ba0-ffffffff81137bb0: do_poweroff (STB_LOCAL)
ffffffff81792600-ffffffff81792633: do_poweroff (STB_LOCAL)
ffffffff81cf56f7-ffffffff81cf5708: do_poweroff.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void do_poweroff(struct work_struct *dummy);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/poweroff.c (ffffffff8115a1f0)
Location: kernel/power/poweroff.c:19
Inline: False
```
```
In drivers/xen/manage.c (ffffffff81ebd86b)
Location: drivers/xen/manage.c:188
Inline: True
```
**Symbols:**

```
ffffffff8115a1f0-ffffffff8115a204: do_poweroff (STB_LOCAL)
ffffffff818cb0c0-ffffffff818cb103: do_poweroff (STB_LOCAL)
ffffffff81ebd86b-ffffffff81ebd87c: do_poweroff.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
void do_poweroff(struct work_struct *dummy);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/poweroff.c (ffffffff8118c4e0)
Location: kernel/power/poweroff.c:19
Inline: False
```
```
In drivers/xen/manage.c (ffffffff81a1c320)
Location: drivers/xen/manage.c:188
Inline: True
```
**Symbols:**

```
ffffffff8118c4e0-ffffffff8118c4f4: do_poweroff (STB_LOCAL)
ffffffff81a1c320-ffffffff81a1c374: do_poweroff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
void do_poweroff(struct work_struct *dummy);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/poweroff.c (ffffffff8119dc00)
Location: kernel/power/poweroff.c:19
Inline: False
```
```
In drivers/xen/manage.c (ffffffff81a654c0)
Location: drivers/xen/manage.c:188
Inline: True
```
**Symbols:**

```
ffffffff8119dc00-ffffffff8119dc14: do_poweroff (STB_LOCAL)
ffffffff81a654c0-ffffffff81a65514: do_poweroff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void do_poweroff(struct work_struct *dummy);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/poweroff.c (ffffffff811acd70)
Location: kernel/power/poweroff.c:19
Inline: False
```
```
In drivers/xen/manage.c (ffffffff81ab7d20)
Location: drivers/xen/manage.c:188
Inline: True
```
**Symbols:**

```
ffffffff811acd70-ffffffff811acd84: do_poweroff (STB_LOCAL)
ffffffff81ab7d20-ffffffff81ab7d74: do_poweroff (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
void do_poweroff(struct work_struct *dummy);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/poweroff.c (ffff800010171b90)
Location: kernel/power/poweroff.c:19
Inline: False
```
```
In drivers/xen/manage.c (ffff80001082f3d0)
Location: drivers/xen/manage.c:187
Inline: False
```
**Symbols:**

```
ffff800010171b90-ffff800010171bac: do_poweroff (STB_LOCAL)
ffff80001082f3d0-ffff80001082f428: do_poweroff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void do_poweroff(struct work_struct *dummy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/poweroff.c (c03c4510)
Location: kernel/power/poweroff.c:19
Inline: False
```
**Symbols:**

```
c03c4510-c03c452c: do_poweroff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void do_poweroff(struct work_struct *dummy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/poweroff.c (c0000000001ca3a0)
Location: kernel/power/poweroff.c:19
Inline: False
```
**Symbols:**

```
c0000000001ca3a0-c0000000001ca3d4: do_poweroff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void do_poweroff(struct work_struct *dummy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/poweroff.c (ffffffe00010de5c)
Location: kernel/power/poweroff.c:19
Inline: False
```
**Symbols:**

```
ffffffe00010de5c-ffffffe00010de7e: do_poweroff (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Transformation ⚠️</summary>

```c
void do_poweroff(struct work_struct *dummy);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/poweroff.c (ffffffff81109cc0)
Location: kernel/power/poweroff.c:19
Inline: False
```
```
In drivers/xen/manage.c (0)
Location: drivers/xen/manage.c:221
Inline: False
```
**Symbols:**

```
ffffffff81109cc0-ffffffff81109cd0: do_poweroff (STB_LOCAL)
ffffffff8162b3f0-ffffffff8162b423: do_poweroff (STB_LOCAL)
ffffffff8162b8a5-ffffffff8162b8b6: do_poweroff.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void do_poweroff(struct work_struct *dummy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/poweroff.c (ffffffff810faba0)
Location: kernel/power/poweroff.c:19
Inline: False
```
**Symbols:**

```
ffffffff810faba0-ffffffff810fabb0: do_poweroff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Transformation ⚠️</summary>

```c
void do_poweroff(struct work_struct *dummy);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/poweroff.c (ffffffff81107bb0)
Location: kernel/power/poweroff.c:19
Inline: False
```
```
In drivers/xen/manage.c (0)
Location: drivers/xen/manage.c:187
Inline: False
```
**Symbols:**

```
ffffffff81107bb0-ffffffff81107bc0: do_poweroff (STB_LOCAL)
ffffffff81659690-ffffffff816596c3: do_poweroff (STB_LOCAL)
ffffffff81659a8c-ffffffff81659a9d: do_poweroff.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Transformation ⚠️</summary>

```c
void do_poweroff(struct work_struct *dummy);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/poweroff.c (ffffffff81112f60)
Location: kernel/power/poweroff.c:19
Inline: False
```
```
In drivers/xen/manage.c (0)
Location: drivers/xen/manage.c:187
Inline: False
```
**Symbols:**

```
ffffffff81112f60-ffffffff81112f70: do_poweroff (STB_LOCAL)
ffffffff81673c90-ffffffff81673cc3: do_poweroff (STB_LOCAL)
ffffffff8167408c-ffffffff8167409d: do_poweroff.cold (STB_LOCAL)
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

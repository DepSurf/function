# Function: <code>pci_bus_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_bus_unlock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81434bc0)
Location: drivers/pci/pci.c:3874
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_bus
```
**Symbols:**

```
ffffffff81434bc0-ffffffff81434c08: pci_bus_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_bus_unlock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81480530)
Location: drivers/pci/pci.c:4195
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_bus
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
```
**Symbols:**

```
ffffffff81480530-ffffffff81480578: pci_bus_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_bus_unlock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a1b80)
Location: drivers/pci/pci.c:4233
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_bus
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
```
**Symbols:**

```
ffffffff814a1b80-ffffffff814a1bc8: pci_bus_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_bus_unlock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ab790)
Location: drivers/pci/pci.c:4387
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_bus
  - drivers/pci/pci.c:pci_reset_bus
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
```
**Symbols:**

```
ffffffff814ab790-ffffffff814ab7da: pci_bus_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_bus_unlock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814eaa80)
Location: drivers/pci/pci.c:4407
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
```
**Symbols:**

```
ffffffff814eaa80-ffffffff814eaaca: pci_bus_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_bus_unlock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81519f20)
Location: drivers/pci/pci.c:4654
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_bus
  - drivers/pci/pci.c:pci_reset_bus
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
```
**Symbols:**

```
ffffffff81519f20-ffffffff81519f68: pci_bus_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_bus_unlock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8152fcb0)
Location: drivers/pci/pci.c:4945
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
```
**Symbols:**

```
ffffffff8152fcb0-ffffffff8152fcf8: pci_bus_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_bus_unlock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8155f490)
Location: drivers/pci/pci.c:5043
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
```
**Symbols:**

```
ffffffff8155f490-ffffffff8155f4d8: pci_bus_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_bus_unlock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815805d0)
Location: drivers/pci/pci.c:5173
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
```
**Symbols:**

```
ffffffff815805d0-ffffffff81580618: pci_bus_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_unlock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162c0a6)
Location: drivers/pci/pci.c:5203
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_trylock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_trylock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff81628420-ffffffff816286e9: pci_bus_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_unlock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81651df6)
Location: drivers/pci/pci.c:5271
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_trylock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_trylock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff8164e640-ffffffff8164e909: pci_bus_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_unlock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816348e6)
Location: drivers/pci/pci.c:5320
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff81631250-ffffffff8163152e: pci_bus_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_unlock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a49d6)
Location: drivers/pci/pci.c:5510
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff816a0ae0-ffffffff816a0dbe: pci_bus_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_unlock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c6e36)
Location: drivers/pci/pci.c:5606
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff817c2870-ffffffff817c2b7e: pci_bus_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_unlock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e42db)
Location: drivers/pci/pci.c:5543
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff818df5f0-ffffffff818df8fe: pci_bus_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_unlock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81922daa)
Location: drivers/pci/pci.c:5665
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff81922a50-ffffffff81922d5e: pci_bus_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_unlock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196b32a)
Location: drivers/pci/pci.c:5775
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff8196afd0-ffffffff8196b2de: pci_bus_unlock (STB_LOCAL)
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
void pci_bus_unlock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e3090)
Location: drivers/pci/pci.c:5173
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
```
**Symbols:**

```
ffff8000106e3090-ffff8000106e30e8: pci_bus_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_bus_unlock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c087ef4c)
Location: drivers/pci/pci.c:5173
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
```
**Symbols:**

```
c087ef4c-c087efa0: pci_bus_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_bus_unlock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085ce90)
Location: drivers/pci/pci.c:5173
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
```
**Symbols:**

```
c00000000085ce90-c00000000085cf10: pci_bus_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_bus_unlock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004ba96a)
Location: drivers/pci/pci.c:5173
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
```
**Symbols:**

```
ffffffe0004ba96a-ffffffe0004ba9c2: pci_bus_unlock (STB_LOCAL)
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
void pci_bus_unlock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81574af0)
Location: drivers/pci/pci.c:5173
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
```
**Symbols:**

```
ffffffff81574af0-ffffffff81574b38: pci_bus_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_bus_unlock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81563250)
Location: drivers/pci/pci.c:5173
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
```
**Symbols:**

```
ffffffff81563250-ffffffff81563298: pci_bus_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_bus_unlock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81574320)
Location: drivers/pci/pci.c:5173
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
```
**Symbols:**

```
ffffffff81574320-ffffffff81574368: pci_bus_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_bus_unlock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158e800)
Location: drivers/pci/pci.c:5173
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
```
**Symbols:**

```
ffffffff8158e800-ffffffff8158e848: pci_bus_unlock (STB_LOCAL)
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

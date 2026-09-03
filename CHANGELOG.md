# Changelog

This changelog describes changes to the structure of the data files, starting 2026-09-02.

## 2026-09-02

- All versions
  - `mimex-blocks.txt`:
    - New attributes `iptDefault`, `iptLimit` and `instructionScale` for logic blocks. Note that `iptLimit` only applies to wrold processors, the non-privileged processors are limited to `iptDefault`. 

## 2026-09-02

- Version `BE`
  - `mimex-laccess.txt`:
    - The `sensor` attribute now specifies whether the `LAccess` property is available in a non-privileged processor.   
    - A new `privileged` attribute specifies whether the `LAccess` property is available in a privileged processor. 

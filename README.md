# Scoop Bucket for Ailoop

Install [ailoop](https://github.com/goailoop/ailoop) via Scoop on Windows.

## Installation

### Option 1: Add Bucket (Recommended)

This method enables automatic updates via `scoop update`:

```powershell
scoop bucket add goailoop https://github.com/goailoop/scoop
scoop install ailoop
```

### Option 2: Direct Install (Single Line)

Install directly from the manifest URL without adding a bucket:

```powershell
scoop install https://raw.githubusercontent.com/goailoop/scoop/main/bucket/ailoop.json
```

Note: This method does not track updates automatically.

## Usage

```powershell
ailoop --version
```

## Upgrading

```powershell
scoop update ailoop
```

## Uninstalling

```powershell
scoop uninstall ailoop
scoop bucket rm goailoop
```

## Learn More

- [Ailoop GitHub](https://github.com/goailoop/ailoop)

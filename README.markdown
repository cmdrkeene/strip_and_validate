# Install

## 1. Clone the repo
    
    git clone git://github.com/cmdrkeene/strip_and_validate.git StripAndValidate.tmbundle

## 2. Reload bundles

    osascript -e 'tell app "TextMate" to reload bundles'

## 3. Change Scope Selector to 'source.ruby'

Open the bundle editor, find the macro called "Strip and Syntax Check" and enter "source.ruby" in the Scope Selector field (below Key Equivalent)

This will ensure that this only runs on ruby files. Junky, but functional.

# Conflict with RSpec

If you use the RSpec.tmbundle, you need remap the key equivalent for the 
"Save Example file and remember" command (It is defaulted to Option+S)

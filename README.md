# spiffyterm
My preferred terminal setup for Mac.

<img width="651" alt="screenshotMLP" src="https://user-images.githubusercontent.com/107746699/180394193-4572985a-cb2e-426b-9cde-a8945e6d4462.png">

How to:
  1. Install Homebrew
  
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    
    
  2. Install iTerm2
  
    brew install --cask iterm2
    
  3. Install git (if not already installed from xcode tools)
  
    brew install git
    
    
  4. Install oh-my-zsh
  
    sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
    
    
  5. Install the fonts
    
    git clone https://github.com/moreleftpedal/spiffyterm
    
    
  6. Install the Powerlevel 10K Theme
    
    git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k
    
    Set the theme on .zshrc file: ZSH_THEME="powerlevel10k/powerlevel10k"
    
    
  7. Install custom iTerm Profile or Colors
    
    Import either my .json profile or just the colors using the .itermcolors file into iTerm. These came in the spiffyterm folder.  
    
    
  8. Set font in iTerm
    
    Set font to MesloLGS NF Regular for best compatibility with PowerLevel10K.  
    
    
  9. Configure PowerLevel10K
    
    Re-lauch iTerm2 and follow promts.  
    
    
  10. Enable suggestions
    
    git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
    
    Add plugin to .zshrc file: plugins=(zsh-autosuggestions)
    
    
  11. Configure VS Code (if you use VS Code)
    
    Update terminal.integrated.fontFamily setting to 'MesloLGS NF'
    
    
Steps for install in Ubuntu Desktop:  I suggest following this tutorial:  https://www.youtube.com/watch?v=PZTLIVQxxEY


Steps for Ubuntu Server:

  1. Install ZSH
  
    sudo apt install zsh
 
 
  2. Switch to ZSH as your default shell. 
  
    Check your current shell:  echo $0
    Switch to ZSH:  chsh 
    Type: /bin/zsh
    Logout and Login for changes to take effect.  
    Now run through configuration on first start up. I suggest using option 2.  
  
  
  3. Install oh-my-zsh
  
    sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
  
  
  4. Install the Powerlevel 10K Theme
    
    git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k
    
    Set the theme on .zshrc file: ZSH_THEME="powerlevel10k/powerlevel10k"
  
    
  5. Configure PowerLevel10K
    
    Re-lauch a terminal and follow promts.  
    
    
  6. Enable suggestions
    
    git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
    
    Add plugin to .zshrc file: plugins=(zsh-autosuggestions)
    


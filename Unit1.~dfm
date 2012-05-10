object Form1: TForm1
  Left = 584
  Top = 126
  Width = 310
  Height = 255
  BorderIcons = [biSystemMenu, biMinimize]
  Caption = 'Killa[h] Tools for RealOTS'
  Color = clBtnFace
  Font.Charset = DEFAULT_CHARSET
  Font.Color = clWindowText
  Font.Height = -11
  Font.Name = 'MS Sans Serif'
  Font.Style = []
  FormStyle = fsStayOnTop
  OldCreateOrder = False
  OnClose = FormClose
  OnCreate = FormCreate
  PixelsPerInch = 96
  TextHeight = 13
  object Label1: TLabel
    Left = 0
    Top = 204
    Width = 294
    Height = 13
    Cursor = crHandPoint
    Align = alBottom
    Alignment = taCenter
    Caption = 'Copyleft 2012 by Killa[h] Forge'
    OnClick = Label1Click
    OnMouseEnter = Label1MouseEnter
    OnMouseLeave = Label1MouseLeave
  end
  object Label3: TLabel
    Left = 0
    Top = 191
    Width = 294
    Height = 13
    Align = alBottom
    Alignment = taCenter
    Caption = 'There are 0 players online!'
    OnClick = Label3Click
  end
  object PageControl1: TPageControl
    Left = 0
    Top = 29
    Width = 294
    Height = 162
    ActivePage = TabSheet2
    Align = alClient
    TabOrder = 0
    object TabSheet1: TTabSheet
      Caption = 'Status'
      DesignSize = (
        286
        134)
      object GroupBox1: TGroupBox
        Left = 0
        Top = 0
        Width = 281
        Height = 127
        Anchors = [akLeft, akTop, akRight, akBottom]
        Caption = ' Characters: '
        PopupMenu = PopupMenu1
        TabOrder = 0
        DesignSize = (
          281
          127)
        object ListBox1: TListBox
          Left = 8
          Top = 16
          Width = 267
          Height = 103
          Anchors = [akLeft, akTop, akRight, akBottom]
          ItemHeight = 13
          TabOrder = 0
          OnDblClick = ListBox1DblClick
        end
      end
    end
    object TabSheet2: TTabSheet
      Caption = 'General Config'
      ImageIndex = 1
      DesignSize = (
        286
        134)
      object GroupBox2: TGroupBox
        Left = 0
        Top = 0
        Width = 285
        Height = 49
        Anchors = [akLeft, akTop, akRight]
        Caption = ' Window Title '
        TabOrder = 0
        DesignSize = (
          285
          49)
        object Edit1: TEdit
          Left = 6
          Top = 20
          Width = 273
          Height = 21
          Anchors = [akLeft, akTop, akRight]
          TabOrder = 0
          Text = '[<name>] Lvl. <level>, Exp: <exp> (<expleft>), <expph> exp/h'
        end
      end
      object GroupBox3: TGroupBox
        Left = 0
        Top = 48
        Width = 285
        Height = 41
        Anchors = [akLeft, akTop, akRight]
        Caption = ' Light '
        TabOrder = 1
        object CheckBox2: TCheckBox
          Left = 64
          Top = 16
          Width = 169
          Height = 17
          Caption = 'Lightup the others!'
          TabOrder = 0
        end
        object CheckBox1: TCheckBox
          Left = 8
          Top = 16
          Width = 49
          Height = 17
          Caption = 'Light'
          TabOrder = 1
        end
      end
    end
    object TabSheet3: TTabSheet
      Caption = 'Alerts'
      Enabled = False
      ImageIndex = 2
      DesignSize = (
        286
        134)
      object GroupBox4: TGroupBox
        Left = 1
        Top = 0
        Width = 285
        Height = 73
        Anchors = [akLeft, akTop, akRight]
        Caption = ' Runemaking '
        TabOrder = 0
        DesignSize = (
          285
          73)
        object CheckBox3: TCheckBox
          Left = 8
          Top = 16
          Width = 41
          Height = 17
          Caption = 'Idle'
          TabOrder = 0
        end
        object CheckBox4: TCheckBox
          Left = 8
          Top = 32
          Width = 65
          Height = 17
          Caption = 'Mana at:'
          TabOrder = 1
        end
        object SpinEdit1: TSpinEdit
          Left = 80
          Top = 28
          Width = 193
          Height = 22
          Anchors = [akLeft, akTop, akRight]
          MaxValue = 0
          MinValue = 0
          TabOrder = 2
          Value = 0
        end
        object CheckBox5: TCheckBox
          Left = 8
          Top = 48
          Width = 57
          Height = 17
          Caption = 'Soul at:'
          TabOrder = 3
        end
        object SpinEdit2: TSpinEdit
          Left = 80
          Top = 44
          Width = 193
          Height = 22
          Anchors = [akLeft, akTop, akRight]
          MaxValue = 0
          MinValue = 0
          TabOrder = 4
          Value = 0
        end
      end
    end
  end
  object Panel1: TPanel
    Left = 0
    Top = 0
    Width = 294
    Height = 29
    Align = alTop
    TabOrder = 1
    DesignSize = (
      294
      29)
    object Label2: TLabel
      Left = 8
      Top = 8
      Width = 49
      Height = 13
      Caption = 'Character:'
    end
    object ComboBox1: TComboBox
      Left = 68
      Top = 4
      Width = 221
      Height = 21
      Anchors = [akLeft, akTop, akRight]
      ItemHeight = 13
      TabOrder = 0
      Text = 'Select character...'
    end
  end
  object PopupMenu1: TPopupMenu
    Left = 144
    Top = 128
    object Refresh1: TMenuItem
      Caption = 'Refresh'
      ShortCut = 116
      OnClick = Refresh1Click
    end
  end
  object Timer1: TTimer
    Interval = 100
    OnTimer = Timer1Timer
    Left = 176
    Top = 128
  end
  object Timer2: TTimer
    Interval = 450000
    OnTimer = Timer2Timer
    Left = 216
    Top = 120
  end
  object Timer3: TTimer
    Interval = 100
    OnTimer = Timer3Timer
    Left = 248
    Top = 120
  end
  object IdHTTP1: TIdHTTP
    MaxLineAction = maException
    ReadTimeout = 0
    AllowCookies = True
    HandleRedirects = True
    RedirectMaximum = 40
    ProxyParams.BasicAuthentication = False
    ProxyParams.ProxyPort = 0
    Request.ContentLength = -1
    Request.ContentRangeEnd = 0
    Request.ContentRangeStart = 0
    Request.ContentType = 'text/html'
    Request.Accept = 'text/html, */*'
    Request.BasicAuthentication = False
    Request.UserAgent = 'Mozilla/3.0 (compatible; Indy Library)'
    HTTPOptions = [hoForceEncodeParams]
    Left = 4
    Top = 112
  end
end

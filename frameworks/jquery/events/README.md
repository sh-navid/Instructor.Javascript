# JQuery
## Events
- Event on DOM
    - .resize()
    - .scroll()
    - .ready()
    - .click(), .dblclick()
    - .focus(), .blur()
    - .focusin(), .focusout()
    - .hover()
    - Bind
        - .on()
        - .off()
        - .one()
        - .bind()
    - Edit
        - .input()
        - .change()
        - .select()
    - Keyboard
        - .keydown()
        - .keyup()
        - .keypress()
    - Mouse
        - .mouseleave()
        - .mousedown()
        - .mouseenter()
        - .mousemove()
        - .mouseout()
        - .mouseover()
        - .mouseup()
    - Deprecated
        - ~~.live(), .die()~~
        - ~~.load()~~
- Event Object
    - Methods
        - event.preventDefault()
            - event.isDefaultPrevented()
        - event.stopPropagation()
            - event.isPropagationStopped()
        - event.stopImmediatePropagation()
            - event.isImmediatePropagationStopped()
    - Attributes
        - Target
            - event.target
            - event.relatedTarget
            - event.currentTarget
            - event.delegateTarget
        - Position
            - event.pageX
            - event.pageY
        - Other
            - event.result
            - event.data
            - event.metaKey
            - event.timeStamp
            - event.type
            - event.which
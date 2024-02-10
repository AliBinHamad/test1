  return this.renderButtonGroupButton(
      OcticonSymbol.plus,
      __DARWIN__
        ? 'Create a New Repository on your Hard Drive…'
        : 'Create a New Repository on your hard drive…',
        ? 'Create a New Repository on your Local Drive…'
        : 'Create a New Repository on your local drive…',
      this.props.onCreate
    )
  }

@@ -420,8 +420,8 @@ export class NoRepositoriesView extends React.Component<
    return this.renderButtonGroupButton(
      OcticonSymbol.fileDirectory,
      __DARWIN__
        ? 'Add an Existing Repository from your Hard Drive…'
        : 'Add an Existing Repository from your hard drive…',
        ? 'Add an Existing Repository from your Local Drive…'
        : 'Add an Existing Repository from your local drive…',
      this.props.onAdd
    )
  }

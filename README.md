# wod

匯入油猴可能亂碼導致失效(原因不明, 求教)
請匯入後自行修改75及98-102行
75:
      const match = /^(?<rollType>.+)公式?：(?<rollCalculation>.+?)( \((?<modifier>[+\-]\d*%?)\))?$/g.exec( $( this ).text() );
98-102:
    replaced = replaced.replaceAll( '×', '*' );
    replaced = replaced.replaceAll( '÷', '/' );
    replaced = replaced.replaceAll( '２', '2' );
    replaced = replaced.replaceAll( '３', '3' );
    replaced = replaced.replaceAll( '＋', '+' );
